--查code缺值
select code_name,deal_type_detail,count(1)as cnt from ec.deal 
where code is null group by code_name,deal_type_detail

--補'美容家電'code值
--select * from ec.deal_type where code_id=74
update ec.deal_type set code='2915' where code_id=74
--select deal_type_detail ,  code_name , code, item_name  from ec.deal where deal_type_detail='74'
update ec.deal set code='2915' where deal_type_detail='74'

--補'有機食品'code值
--select * from ec.deal_type where code_id=86
update ec.deal_type set code='412' where code_id=86
select deal_type_detail ,  code_name , code, item_name  from ec.deal where deal_type_detail='86'
--update ec.deal set code='412' where deal_type_detail='86'

--補'保健纖體'code值
--select * from ec.deal_type where code_id=38
update ec.deal_type set code='2890' where code_id=38
--select deal_type_detail ,  code_name , code, item_name  from ec.deal where deal_type_detail='38'
update ec.deal set code='2890' where deal_type_detail='38'

--補'被毯枕睡袋'code值
--select * from ec.deal_type where code_id=80
update ec.deal_type set code='569' where code_id=80
--select deal_type_detail ,  code_name , code, item_name  from ec.deal where deal_type_detail='80'
update ec.deal set code='569' where deal_type_detail='80

--補'兒童/幼兒書籍'code值
--select * from ec.deal_type where code_id=87
update ec.deal_type set code='5529' where code_id=87
--select deal_type_detail ,  code_name , code, item_name  from ec.deal where deal_type_detail='87'
update ec.deal set code='5529' where deal_type_detail='87'
