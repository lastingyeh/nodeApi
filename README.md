### Run Server

  at .zsh

  1. yarn dev:build

  2. yarn dev (hot-reload)

### Use API

  1. Signup 

  2. Login

  3. CreatePost

  4. GetById

  5. GetAllPosts

  6. PathById

  7. DeleteById

  8. PostFavoriteById

### Project structure

  - index

    - config

      - constants (connectionString,port,...)

      - database (db connection)

      - middlewares (middlewares used)

    - modules

      - posts

        - post.controllers (defined post methods implemented)

        - post.model (PostSchema, methods settings)

        - post.routes (createPost,getPostById,getPostsList,updatePost,deletePost,favoritePost)

        - post.validations (use Joi for validations of PostSchema)

      - users

        - user.controller (defined singUp,login methods implemented)

        - user.model (UserSchema, methods settings)

        - user.routes (signUp,login)

        - user.validations (use Joi for validations of UserSchema)

    - services

        - auth.services (defined localStrategy,jwtStrategy Authentication)

### Process run

get api data > routes > validations > controller 
                                    > model 

### Refs

https://www.youtube.com/watch?v=tuftcAdw8yc&list=PLzQWIQOqeUSMzMUEJA0XrOxJbX8WTiCJV&index=12

https://github.com/EQuimper/youtube-makeanodejsapi

                            
