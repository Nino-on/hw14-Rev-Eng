
--Password Authenication--

This app allows users to create an account, log into the account and sign back out securely. All user data is stored in a mysql database.

--Tech used --

-EXPRESS -EXPRESS-SESSION -MYSQL2 -PASSPORT -PASSPORT-LOCAL -SEQUELIZE


--Files used--  

isAuthenticated.js {  limits routes user is not allow to go to if not logged on and if they are logged continues };
config.json { connect to server };

passport.js { has  javascript info that tells passport what to log in with an email address and password };

MODELS

user.js { You need to use bcrypt for the password. To make database secure in cause it get hacked and the JS tells what  is saved in the database
};


index.js { makes Database and brings in user log in the data }; 

ROUTES

package.json { has all the package info and the modules need to be used in node.}; 

api-routes.js { chas routes for signing in, logging out and getting users specific data to be displayed client side };

html-routes.js { checks whether user is signed in, if the user has account and sends the to the html page };


server.js { needs packages, sets up PORT, creates express and middleware, makes routes and syncs database  };

