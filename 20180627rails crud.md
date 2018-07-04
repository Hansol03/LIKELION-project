# rails crud

- rails g controller posts index new create show edit update destroy 
- rails g model post title:string content:text
- rake db:migrate



# Restful

#Create
  get 'posts/new'
  post 'posts' => "posts#create"

# Read
#Create
  get 'posts/new'
  post 'posts' => "posts#create"

# Read
```ruby
#Create
  get 'posts/new'
  post 'posts' => "posts#create"

# Read
  get 'posts/:id' => "posts#show"

#Update
  get 'posts/:id/edit' => "posts#edit"
  put 'posts/:id' => "posts#update"
  
#Delete
  delete 'posts/:id' => "posts#destroy"
  
```



