# HelloPhoenix

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

# possible gems to find:
- api serializer (or ja_serializer try remodel - Associations could be problematic)
- comeonin(for bcrypt in elixir)
- cors_plug (for mobile app / external service communication)
- deps: deps/phoenix/web/static/js/phoenix.js, deps/phoenix_html/web/static/js/phoenix_html.js

# Concerns
- make phoenix/elixir read assets.json and use it in the layout files(priv/static/js/ is the compiled directory)
- paper_trail (none - biggest problem), paper_trail isnt perfect either
- session support is problematic in Elixir (for distributed systems - problematic = minor)
- railroady
- slugs (problematic, not much native support is better than ruby)
- search (few libraries, should be done on database level)
- global_phone (good to have)

do deployment
user authentication
api authentication
check jwt again

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
