Quick demo of using a custom devise strategy to log in from a token passed through a header

See [this commit](https://github.com/TIY-DC-ROR-2015-May/token-auth-demo/commit/d8a4c0f7a5616e514642cb44117dda275ba4a557) for a quick up-and-running auth system with a hardcoded token and user.

See [Ferrite's strategy](https://github.com/jamesdabbs/ferrite/blob/master/config/initializers/devise.rb) (and corresponding [token model](https://github.com/jamesdabbs/ferrite/blob/master/app/models/auth_token.rb)) for a more realistic implementation.
