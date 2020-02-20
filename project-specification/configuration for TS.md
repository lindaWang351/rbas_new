# RBAS 系統結構

![a4035baf](pictures/rbas_spec_layout.PNG)

## Transaction Server api

### TS register

```json
{
    "PS_hash": "hhhhhhhh",
    "TS": [
        {
        "TS_id": {
            "name": "name",
            "IP": "iii.iii.iii.iii",
            "port": "pppp",
            "geo": {
                "latitude": "ll.llll",
                "longitude": "ll.llll"},
                "manager": [
                    {
                        "operator": {
                            "name": "nnnn",
                            "mobile": "mmmmmmmm",
                            "email": "eeeeeeeeee"}
                        },
                    {
                        "operator": {
                            "name": "nnnn",
                            "mobile": "mmmmmmmm",
                            "email": "eeeeeeeeee"}
                        }
                    ]
                }
            }
        ]
    }

{
    "api_type": "PS>all_local_TS",
    "pre_hash_for_each_TS": "hhhhhhhh",
    "cycle": "nnnnnnnnnn",
    "time": "yyyy-mm-dd,HH:MM:SS"
    }
```

### TS to PS log_in connection

```json
{
    "TS_name": "name",
    "real-time-password":"pppppp"}

{
    "api_type": "PS>all_local_TS",
    "pre_hash_for_each_TS": "hhhhhhhh",
    "cycle": "nnnnnnnnnn",
    "time": "yyyy-mm-dd,HH:MM:SS"
    }
```

### TS upload t_hash

```json
{
    "api_type": "TS>PS",
    "cycle": "nnnnnnnnnn",
    "T_hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
    }

{
    "api_type": "next PS>all_local_TS",
    "pre_hash_for_each_TS": "hhhhhhhh",
    "cycle": "nnnnnnnnnn",
    "time": "yyyy-mm-dd,HH:MM:SS"
    }
```
