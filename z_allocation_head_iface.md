# z_allocation_head_iface
|  列名   | 类型  |	 说明  |
|  ----  | ----  |	----  |
|TENANT_ID               |bigint(20)     	|租户id                                                  |             
|IFACE_ID                |bigint(20)     	|主键                                                    |             
|INSTRUCTION_DOC_NUM     |varchar(255)   	|调拨单编码                                              |          
|INSTRUCTION_DOC_TYPE    |varchar(255)   	|单据类型                                                |           
|INSTRUCTION_DOC_STATUS  |varchar(255)   	|调拨单状态                                              |          
|SITE_ID                 |varchar(100)   	|站点id                                                  |             
|SITE_CODE               |varchar(255)   	|工厂代码                                                |           
|PERSON_ID               |varchar(100)   	|申请人/领料人                                           |         
|DEMAND_TIME             |datetime       	|需求时间                                                |           
|EXPECTED_ARRIVAL_TIME   |datetime       	|预计送达时间                                            |         
|REMARK                  |varchar(1000)  	|备注                                                    |             
|REASON                  |varchar(1000)  	|原因                                                    |             
|STATUS                  |varchar(100)   	|状态(新增数据时默认为N，失败为E，成功S，处理中P)        |
|CID                     |bigint(100)    	|                                                        |               
|OBJECT_VERSION_NUMBER   |bigint(20)     	|                                                        |               
|CREATED_BY              |bigint(20)     	|                                                        |               
|CREATION_DATE           |datetime       	|                                                        |               
|LAST_UPDATED_BY         |bigint(20)     	|                                                        |               
|LAST_UPDATE_DATE        |datetime       	|                                                        |               



