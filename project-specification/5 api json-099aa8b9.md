# heart-beat cycle start

```json
[
	{
		"api_type": "RS>all_local_PS",
		"prv_hash_for_each_PS": "hhhhhhhh",
		"cycle": "nnnnnnnnnn",
		"time": "yyyy-mm-dd,HH:MM:SS"
	},
	{
		"api_type": "PS>all_local_TS",
		"pre_hash_for_each_TS": "hhhhhhhh",
		"cycle": "nnnnnnnnnn",
		"time": "yyyy-mm-dd,HH:MM:SS"
	},
	{
		"api_type": "TS>PS",
		"cycle": "nnnnnnnnnn",
		"T_hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
	},
	{
		"api_type": "PS>all_DB_T",
		"cycle": "nnnnnnnnnn",
		"RS_PS_ID": "RSid_PSid",
		"add T_hash": [
			"hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh",
			"hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
		]
	},
	{
		"api_type": "PS>all_DB_C",
		"cycle": "nnnnnnnnnn",
		"RS_PS_ID": "RSid_PSid",
		"add T_hash": [
			"hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh",
			"hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
		]
	},
	{
		"api_type": "DB_T>all_RS",
		"cycle": "nnnnnnnnnn",
		"T_hash_this_cycle_local_RS": "nnnnnnnnnn",
		"total-T_hash": "nnnnnnnnnnnn",
		"DB_T-hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
	},
	{
		"api_type": "DB_C>all_RS",
		"cycle": "nnnnnnnnnn",
		"T_hash_this_cycle_local_RS": "nnnnnnnnnn",
		"total-T_hash": "nnnnnnnnnnnn",
		"query_this_cycle": "nnnnnn",
		"fault_query_this_cycle": "nnnnnn",
		"DB_C-hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
	},
	{
		"api_type": "QS>DB_C",
		"RS_QS_ID": "RSid_QSid",
		"?hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
	},
	{
		"api_type": "DB_C>QS",
		"valid": true,
		"cycle": "nnnnnnnnnn",
		"time": "yyyy-mm-dd,HH:MM:SS"
	},
	{
		"api_type": "RS>all_dashboard",
		"cycle": "nnnnnnnnnn",
		"time": "yyyy-mm-dd,HH:MM:SS",
		"RS_info": [
			{ "name": "nnnnnn" },
			{ "geo_Long": "nn.nn" },
			{ "geo_lad": "nn.nn" }
		],
		"T_hash_this_cycle_local_RS": "nnnnnnnnnn",
		"total-T_hash": "nnnnnnnnnnnn",
		"DB_T-hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh",
		"query_this_cycle": "nnnnnn",
		"fault_query_this_cycle": "nnnnnn",
		"DB_C-hash": "hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh.hhhhhhhh"
	}
]
```

# TS upload t_hash

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
