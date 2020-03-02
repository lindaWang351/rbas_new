# RS Server api

```json
[
	{
		"RS_id": {
			"name": "name",
			"IP": "iii.iii.iii.iii",
			"port": "pppp",
			"geo": {
				"latitude": "ll.llll",
				"longitude": "ll.llll"
			},
			"manager": [
				{
					"operator": {
						"name": "nnnn",
						"mobile": "mmmmmmmm",
						"email": "eeeeeeeeee"
					}
				},
				{
					"operator": {
						"name": "nnnn",
						"mobile": "mmmmmmmm",
						"email": "eeeeeeeeee"
					}
				}
			]
		}
	},
	{
		"RS_id": {
			"name": "name",
			"IP": "iii.iii.iii.iii",
			"port": "pppp",
			"geo": {
				"latitude": "ll.llll",
				"longitude": "ll.llll"
			},
			"manager": [
				{
					"operator": {
						"name": "nnnn",
						"mobile": "mmmmmmmm",
						"email": "eeeeeeeeee"
					}
				},
				{
					"operator": null
				}
			]
		}
	},
	{ "RS_id": null }
]
```

# PS register

```json
{
	"RS_hash": "hhhhhhhh",
	"DB": {
		"T_DB_ip": "iii.iii.iii.iii",
		"C_DB_ip": "iii.iii.iii.iii"
	},

	"PS": [
		{
			"PS_id": {
				"name": "name",
				"IP": "iii.iii.iii.iii",
				"port": "pppp",
				"geo": {
					"latitude": "ll.llll",
					"longitude": "ll.llll"
				},
				"manager": [
					{
						"operator": {
							"name": "nnnn",
							"mobile": "mmmmmmmm",
							"email": "eeeeeeeeee"
						}
					},
					{
						"operator": {
							"name": "nnnn",
							"mobile": "mmmmmmmm",
							"email": "eeeeeeeeee"
						}
					}
				]
			}
		}
	],
	"QS": [
		{
			"QS_id": {
				"name": "name",
				"IP": "iii.iii.iii.iii",
				"port": "pppp"
			}
		}
	]
}
```


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
					"longitude": "ll.llll"
				},
				"manager": [
					{
						"operator": {
							"name": "nnnn",
							"mobile": "mmmmmmmm",
							"email": "eeeeeeeeee"
						}
					},
					{
						"operator": {
							"name": "nnnn",
							"mobile": "mmmmmmmm",
							"email": "eeeeeeeeee"
						}
					}
				]
			}
		}
	]
}


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
                        "operator-1": {
                            "name": "nnnn",
                            "mobile-1": "mmmmmmmm",
                            "email-1": "eeeeeeeeee"}
                        },
                    {
                        "operator-2": {
                            "name": "nnnn",
                            "mobile-1": "mmmmmmmm",
                            "email-1": "eeeeeeeeee"}
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

