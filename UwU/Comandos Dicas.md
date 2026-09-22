
## Migração
migrações pendentes
`php artisan migrate

limpa todas as migrações e popula de novo com SEED
`php artisan migrate:fresh --seed `

migrações executadas
`php artisan migrate:status

executar migração
`php artisan migrate --step`

reverter migração unica ou 
`migrate:rollback` ou `php artisan migrate:rollback`

reverter ultima 5migração
`php artisan migrate:rollback --step=5`

reverter TODAS migracao do app
`php artisan migrate:reset

ver instrurção  executadas pela migração sem real executar
`php artisan migrate --pretend`

forca execucao de migracao
`php artisan migrate --force`


ADD  coluna nova
`php artisan make:migration add_status_to_users_table --table=users 

remover coluna
`php artisan make:migration remove_old_column_from_users_table --table=users`


SHOW FULL PROCESSLIST;