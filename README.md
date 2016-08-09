# Mastering-Android

It is a small app in which we find three screens (List -> Details, Map, Setting in a Dialog):

>Singleton in Application Class

>Recyclerview

>CardView

>DataBase and Louders

>Location Service

>Material designe

Third party libraries:


 - Recyclerview
 - Cardview
 - Palette
 - Gms
 - Retrofit
 - Rxjava
 - Calligraphy
 - Glide

The app is organized as follows:

Adapter

> GlobalPostAdapter, Basic adapter.

> GlobalPostCursorAdapter and GlobalPostCursorAdapterV2, They are adapter using DB cursor.

> TabPageAdapterFragment, Adapter to show the 3 tabs in Top of the screen and the 3 diferent screens.


api
(Http)
> Interface for the Https.

data

> BMAContentProvider, Provide acces to make diferent proces to the data in data base (Delete, Update, Create, Insert, Querys).

> BMADao, Simple Dao DB.

> BMAOpenHelper, Query DB.

> BMATools, Proces the Cursor from DB.

> DatabaseContract, Contract.

listener

> MyRecyclerItemClickListener, Rows Listener (Click in the row of the list).

model

> Pojo, Endpoint JSON to local java object and DB pojo.

ui

actiity

> MainActivity, Load The 3 screens and tabs to navigate.

> DetailActivity, Load the information from the rows do you click.

fragment

> DetailFragment, Show to the user the detail of the row selectec.

> ListCursorAdapterFragment, Show the list using the Content Provider from DB and Louder.

> ListFragment, Show the list using the Cursor from DB and Louder.

> ListFragmentCP, Show the list using Content provider.

> ListFragmentDB, Show the list using the Cursor.

> MyMapFragment, Show Google Maps.

> SettingsFragment, Create alaert Dialog to select an option.

> BookExampleApplication, Is the Application whe init the Api and the Calligraphy.


