
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Rails project on Cloud9 IDE!

To get started, just do the following:

1. Run the project with the "Run Project" button in the menu bar on top of the IDE.
2. Preview your new app by clicking on the URL that appears in the Run panel below (https://blog-davidchen2016.c9users.io/).

Happy coding!
The Cloud9 IDE team


## Support & Documentation

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE. 
To watch some training videos, visit http://www.youtube.com/user/c9ide

---------------------------------------------------------------------------Rails study website:
http://guides.rubyonrails.org/getting_started.html
---------------------------------------------------------------------------To run a Rails application:
rails s -b $IP -p $PORT
---------------------------------------------------------------------------$ rake routes
              Prefix Verb   URI Pattern                                       Controller#Action
       welcome_index GET    /welcome/index(.:format)                          welcome#index
                root GET    /                                                 welcome#index
    article_comments GET    /articles/:article_id/comments(.:format)          comments#index
                     POST   /articles/:article_id/comments(.:format)          comments#create
 new_article_comment GET    /articles/:article_id/comments/new(.:format)      comments#new
edit_article_comment GET    /articles/:article_id/comments/:id/edit(.:format) comments#edit
     article_comment GET    /articles/:article_id/comments/:id(.:format)      comments#show
                     PATCH  /articles/:article_id/comments/:id(.:format)      comments#update
                     PUT    /articles/:article_id/comments/:id(.:format)      comments#update
                     DELETE /articles/:article_id/comments/:id(.:format)      comments#destroy
            articles GET    /articles(.:format)                               articles#index
                     POST   /articles(.:format)                               articles#create
         new_article GET    /articles/new(.:format)                           articles#new
        edit_article GET    /articles/:id/edit(.:format)                      articles#edit
             article GET    /articles/:id(.:format)                           articles#show
                     PATCH  /articles/:id(.:format)                           articles#update
                     PUT    /articles/:id(.:format)                           articles#update
                     DELETE /articles/:id(.:format)                           articles#destroy
---------------------------------------------------------------------------workflows
1. route, controller, action and view (4.2-5.1)
2. df