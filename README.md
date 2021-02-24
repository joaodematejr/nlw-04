# nlw-04
Evento NLW#04

mix archive.install hex phx_new 1.5.7  
mix phx.new rocketpay --no-webpack --no-html

mix ecto.setup
mix deps.get    
mix credo gen.config

mix ecto.create

mix phx.server 

mix ecto.create

mix ecto.gen.migration create_user_table

mix ecto.migrate