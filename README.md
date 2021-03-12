# ElenaLopato.github.io
Сourses

{
	"info": {
		"_postman_id": "a1ac4915-4d1c-4bfd-af31-3c14e9cb6a29",
		"name": "New Collection",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "POST/login",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\n  \"apikey\": \"string\",\n  \"pin\": \"string\"\n}\n"
				},
				"url": {
					"raw": "https://{{base_url}}/v4/login",
					"protocol": "https",
					"host": [
						"{{base_url}}"
					],
					"path": [
						"v4",
						"login"
					]
				},
				"description": "CРѕР·РґР°С‚СЊ С‚РѕРєРµРЅ Р°РІС‚РѕСЂРёР·Р°С†РёРё"
			},
			"response": [
				{
					"name": "POST/login",
					"originalRequest": {
						"method": "POST",
						"header": [
							{
								"key": "Content-Type",
								"value": "application/json",
								"type": "text"
							}
						],
						"body": {
							"mode": "raw",
							"raw": "{\n  \"apikey\": \"string\",\n  \"pin\": \"string\"\n}\n"
						},
						"url": {
							"raw": "https://api4.thetvdb.com/v4/login",
							"protocol": "https",
							"host": [
								"api4",
								"thetvdb",
								"com"
							],
							"path": [
								"v4",
								"login"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Fri, 12 Mar 2021 08:37:46 GMT"
						},
						{
							"key": "Content-Type",
							"value": "application/json; charset=UTF-8"
						},
						{
							"key": "Content-Length",
							"value": "929"
						},
						{
							"key": "Connection",
							"value": "keep-alive"
						}
					],
					"cookie": [],
					"body": "{\n    \"status\": \"success\",\n    \"data\": {\n        \"token\": \"eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJhcGlrZXkiOiJzdHJpbmciLCJjb21tdW5pdHlfc3VwcG9ydGVkIjpmYWxzZSwiZXhwIjoxNjE2MTQzMDY2LCJpZCI6IjAiLCJpc19tb2QiOmZhbHNlLCJpc19zeXN0ZW1fa2V5IjpmYWxzZSwicGluIjoic3RyaW5nIn0.ju2R1c2uex4yolmhytnRKa2Lca9nmj7jQxcZ29gAvZMHtxen5LR0JID8vws9DLNi9WzZFIQI8abDZqedJfjv_rO9EuHz-O8ndo4acKkNBt1eOvRa5zj5OVzMSjzYWWz9ohJYCYSctn8eRK2QITyF32-56GlqfC1MIXeuGcN1XulVjSaFDKs3DoU7n2BdBoT9J_YcXvJhNYxJz3UgtoWHsmiq_cCNVaxg7ho2ae4yCFnMILYRz9TQBX95RUjHHvg3wABv61bfIu0A3uRSEcaOIhthGxcA8_MTF3UIe5mzQbEb2_Mi_ItzTQnaEfFECbhlCYeQoi12ddJ5efkgtcav_JfEC1OJRVSAkcwxaE-A_TGpGqpiVxSHd5FWdFKGnoYu6cjDx01e0LfUNqGmUbdac6sgkQ5qubn-fzzXKc7I-8xUbZzHF7KFm6BVc-A2zTT_tmRcNuPqwF4w4iH3yKV22piNvTZ1MRER6e0o6MmdEAdm8JHsPqYXCPt-H5j_yFbCM9guK9UaVBTtdRVxZ7TQQmtWj1izTAtS9vDf5g48L4JAFMf5abLNszd8THC1mzoF0wDP3gt8wqt3jyfIdHRPb-suA2-j-rfMh_ht1yn6ymXnMeEpjhTtashjxUll6sLrMLRGdfNY-mnj3ac4t_uRDxszcZuOYoe_aVQiCVmo_4o\"\n    }\n}"
				}
			]
		},
		{
			"name": "POST/login 2",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": ""
				},
				"description": "create an auth token"
			},
			"response": [
				{
					"name": "POST/login 2",
					"originalRequest": {
						"method": "POST",
						"header": [
							{
								"key": "Content-Type",
								"value": "application/json",
								"type": "text"
							}
						],
						"body": {
							"mode": "raw",
							"raw": "{\n  \"apikey\": \"string\",\n  \"pin\": \"string\"\n}"
						},
						"url": {
							"raw": "https://api4.thetvdb.com/v4/{{my_variable}}",
							"protocol": "https",
							"host": [
								"api4",
								"thetvdb",
								"com"
							],
							"path": [
								"v4",
								"{{my_variable}}"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Fri, 12 Mar 2021 08:24:15 GMT"
						},
						{
							"key": "Content-Type",
							"value": "application/json; charset=UTF-8"
						},
						{
							"key": "Content-Length",
							"value": "929"
						},
						{
							"key": "Connection",
							"value": "keep-alive"
						}
					],
					"cookie": [],
					"body": "{\n    \"status\": \"success\",\n    \"data\": {\n        \"token\": \"eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJhcGlrZXkiOiJzdHJpbmciLCJjb21tdW5pdHlfc3VwcG9ydGVkIjpmYWxzZSwiZXhwIjoxNjE2MTQyMjU1LCJpZCI6IjAiLCJpc19tb2QiOmZhbHNlLCJpc19zeXN0ZW1fa2V5IjpmYWxzZSwicGluIjoic3RyaW5nIn0.dXZEOYXcCIsOSOP5ZMtNuG2AOQ8P9vJoYXbz57w6NxUKxtzfa-lOV6qDxv4jKf2zGw4bttD0_VyHiZ14iK0hKMYg-CyogY__ndn7ZXs4hNHusDc_y5H-PA7JhOCsOnW8gbSTJbtwNHUztcMEo1kkjTb3E1QdB7SssSAOmFzsd_bitD4ehm7Q2C2TxvprQDbTOZ1ay_EUpVhlSPHuNBIhhQDAgkOqpm4qIeP0PM2uTkN_6DA3jLLbwVFzvvS498yrT_xE_UuAJfjFc6dUeGxXxybNkPFjpJiGcZM9c8mvMDY40LL-WXfYjkyhCRAbXmpzX61iKCGY0WRUNQYpqPDFAfiObT_mFqqEt-xgN39tzbmEm1PHMbQpUA2IQJlQlHlWc7ud0lQ2WjPeOVlw41GHXe3bXkrb0z2uzUkwhGpoPHH3snoZga0w2lv50sr_tsKRaOx4kC9-h2FbcJ3sp50yJdxYrVBjJaqSfawdQWJuvVvtSrxC4RxGJ4M8_Gnuo0xZ0_2rzJRRpYqvzAuko8VW1MniprHDZ_lv5kuHGh3A5-2uKe4SiLDU3oq01vSUXAJPm78sGt9gmlq5k3d5DnTTB6YAsTXgR5hft7ihiMNOzPfqoD1N-Kh6D6tOpahiOaSz-n2-x1Y0U6gwPguA09PG0jDHbA1Iw_i1qDzAhCuLrNE\"\n    }\n}"
				}
			]
		},
		{
			"name": "POST/login 3",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": ""
				},
				"description": "create an auth token"
			},
			"response": [
				{
					"name": "POST/login 3",
					"originalRequest": {
						"method": "POST",
						"header": [
							{
								"key": "Content-Type",
								"value": "application/json",
								"type": "text"
							}
						],
						"body": {
							"mode": "raw",
							"raw": "{\n  \"apikey\": \"string\",\n  \"pin\": \"string\"\n}"
						},
						"url": {
							"raw": "https://{{base_url}}/v4/login",
							"protocol": "https",
							"host": [
								"{{base_url}}"
							],
							"path": [
								"v4",
								"login"
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Fri, 12 Mar 2021 08:26:20 GMT"
						},
						{
							"key": "Content-Type",
							"value": "application/json; charset=UTF-8"
						},
						{
							"key": "Content-Length",
							"value": "929"
						},
						{
							"key": "Connection",
							"value": "keep-alive"
						}
					],
					"cookie": [],
					"body": "{\n    \"status\": \"success\",\n    \"data\": {\n        \"token\": \"eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJhcGlrZXkiOiJzdHJpbmciLCJjb21tdW5pdHlfc3VwcG9ydGVkIjpmYWxzZSwiZXhwIjoxNjE2MTQyMzgwLCJpZCI6IjAiLCJpc19tb2QiOmZhbHNlLCJpc19zeXN0ZW1fa2V5IjpmYWxzZSwicGluIjoic3RyaW5nIn0.rdwjg1KdK_nAUoD2Q_lAD0v8laYyp0fkZ-fwxOn9HpjKBR8jQfFMEP1Zo9EGXWJU8gQJSnQ72qXlZD5Olwk4nqbo9RWMWmQV0pB7IZsVdHYHdV99EOETRkWzlr_MEy0cdEDowBFUUeGU2cqbs58zUNF2NKv0Vij9CCx_Dbs9wOL7osX_uweV6poisyQcECBMtsqFUR8r6WTh3xuODxSbH4Il_QQCMV-hKmlOwT1TY_2_FVu94MF8LNYDG5CKAkM2yoe3s6Vry70ko2n5K0XZkkV_Q9t5PTY3GTiIapVVycmhK5Vs6D0K0hpOG80IDWfUYrEZ1Ai2IxRINdawCYE0f4mVXhtJXPzlLF5gegD1-5_6rwa6N7aZ1Ouy-s0fDSbSmpsMg62nui8ceflEa5KTJcg47QUoeNPZpzdD9lrjH4Qhvju3QQ0LuAdjSmD30lJuixGMObTnGLvjpALmqUYvpRKXASSUdU9s_gXqlVQdUBKLEUzwbxt3t7AXbeQxlgebXav8c7afgql3iM1OqsnIFMWFb0fT_3KRzD24ZaRx3EVBIRtnqX55iQF8KSuB-pEIg-1yEpP5XSQ2CAnVyrw6WCIP-9gzo7-MBW-HLYJbdBdFL3UYbxpm96myD_yqF93USjvV78uq13fXfb2-DgJENJHWwY01VahhmsHwzuPHL8Q\"\n    }\n}"
				}
			]
		},
		{
			"name": "POST/login 4",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "Content-Type",
						"value": "application/json",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\n  \"apikey\": \"string\",\n  \"pin\": \"string\"\n}"
				},
				"url": {
					"raw": "https://api4.thetvdb.com/v4/login?username=veronika_popova",
					"protocol": "https",
					"host": [
						"api4",
						"thetvdb",
						"com"
					],
					"path": [
						"v4",
						"login"
					],
					"query": [
						{
							"key": "username",
							"value": "veronika_popova"
						}
					]
				},
				"description": "create an auth token"
			},
			"response": [
				{
					"name": "POST/login 4",
					"originalRequest": {
						"method": "POST",
						"header": [
							{
								"key": "Content-Type",
								"value": "application/json",
								"type": "text"
							}
						],
						"body": {
							"mode": "raw",
							"raw": "{\n  \"apikey\": \"string\",\n  \"pin\": \"string\"\n}"
						},
						"url": {
							"raw": "https://api4.thetvdb.com/v4/login?{{username}}=veronika_popova",
							"protocol": "https",
							"host": [
								"api4",
								"thetvdb",
								"com"
							],
							"path": [
								"v4",
								"login"
							],
							"query": [
								{
									"key": "{{username}}",
									"value": "veronika_popova"
								}
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Date",
							"value": "Fri, 12 Mar 2021 08:43:24 GMT"
						},
						{
							"key": "Content-Type",
							"value": "application/json; charset=UTF-8"
						},
						{
							"key": "Content-Length",
							"value": "929"
						},
						{
							"key": "Connection",
							"value": "keep-alive"
						}
					],
					"cookie": [],
					"body": "{\n    \"status\": \"success\",\n    \"data\": {\n        \"token\": \"eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJhcGlrZXkiOiJzdHJpbmciLCJjb21tdW5pdHlfc3VwcG9ydGVkIjpmYWxzZSwiZXhwIjoxNjE2MTQzNDA0LCJpZCI6IjAiLCJpc19tb2QiOmZhbHNlLCJpc19zeXN0ZW1fa2V5IjpmYWxzZSwicGluIjoic3RyaW5nIn0.ehT6IaF41NbmyAxWq3BjRFwKZj_aYTKbwLwdykCU3gB9ebKWVP69wDe20Y2JG_-eRTQsI_-kkF7Q1XHDKy4bByJt85QqH7KLPraNRSE7TaiLUZriGqEs7mB7FWEdAqHzlbr4-pGB7sKRZD_Z2rfBrvCgbaSI2k79Qc0voj5CXr7ztVFTT-cDMnoOZI__XWKsrYYEWyji0Ck05rp81nOB4vZOx1qTBGrltem6NL2vGtY7YAEilJ0qt9eCOvVVD0giheXNVgUZ_FLRpTBwLa-hx8qV2ikUGuWz_-GjC3j3T6ROGdGn7suVTWLXxa3kKxdGw6iXfdvoPJRBUGVHcNsjRrgkKWe3CJs8RWyJvWkF10vpDbIybA4q1hsahZjhhx4XZk4smaRx9__0zrs3uoTYpZOCt6RInaLCKsRgk_6NKC49oPD_j4STXleGivYdshxPEQyZ9T3dnu1z5VNXu7q5ZRsbosIQnfZLKvlgxqRuDQG2cT2WZDUDnuHntpXaY4yQ9wLTFjgJGLgRSXvgxlUhLcR4j2Lhufuasyv4Q85v3IMU2gSbzWc5ZKuQSSKjWYwzEqavjPNkfIUqmwIElhw95_CW8vzRAIcEc4c3FwCWk8nlu-eDSk8-bJBH_yYlwKoB8VhmaOhMv5cVrldLVCVm6XIK9lp3xA14KB7qD1Fk2SU\"\n    }\n}"
				}
			]
		}
	]
}
