# Keeping Your Massive Rails App From Turning Into a Shit Show
by [Benjamin Smith (@benjamin_smith)](http://www.twitter.com/benjamin_smith) at Pivotal Labs

##…by Architecting it for Success

Scheduler
Admin
SocialNetwork
Common

all engines

MobileCompass

GlobalAdmin
AdminAssets
ContentAdmin
SocialAdmin

Web Engines/Domain Engines


#### Fully Contained Engines
* All tables namespaced
	* put that table's engine name prepended to it
* Migrations
	* One table per migration
* Tests
	* Test each engine in isolation
	
Engines are black boxes that do one thing and do it well, with this method.

No circular dependencies.
If you ever find you need circular dependencies, you probably want to combine engines, but don't do otherwise.

### domain api
Sits between controllers and models

* simple classes to wrap ActiveRecord calls


### How does this help?
Loose coupling
no circular dependencies
better/easier testing

### Engines are a pain
* missed all of these gah

### …but they get better
* no slow down in development time
* they age well
* easier parallel development
* potential for scaling
* smart and fast build scripts