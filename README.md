# Tolha - โทรหา

> เข้าถึงประวัติการโทรของตัวเองง่ายๆ

## Get Started
```bash
# support python 3.8+
pip install tolha
```

```python
from decouple import config
from tolha.myais import get_recent_call_history

call_usage = get_recent_call_history(config("PHONE_NUMBER"), config("PASSWORD"), config("NATIONAL_ID"))
print(call_usage)
```

### NOTES
This code won't run on jupyter until https://github.com/microsoft/playwright-python/issues/178 is fixed.

## Dev

### Roadmap
1. output as pandas DataFrame
2. able to select other month
3. make cli
4. add other telco

### Tools
use <https://chrome.google.com/webstore/detail/selectorgadget/mhjhnkcfbdhnjickkkdbjoemdmbfginb>
