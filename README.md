ArbiterJS
=========

Written by Matt Kruse
From site http://arbiterjs.com/
This work is in the public domain and may be used in any way, for any purpose, without restriction.

This is full replica of v1.0 - GitHubetize ArbiterJs

    Arbiter.publish
    Arbiter.publish( msg [, data [, options] ] )
    Returns: true on success, false if any subscriber has thrown a js exception
			
Arbiter.subscribe
    Arbiter.subscribe( msg, func )
    Arbiter.subscribe( msg, options, func )
    Arbiter.subscribe( msg, options, context, func )
    Returns: subscription id
             or [id1,id2] if subscribing to multiple messages
			
Arbiter.unsubscribe
    Arbiter.unsubscribe( subscription_id )

Arbiter.resubscribe
    Arbiter.resubscribe( subscription_id )

Arbiter.create
    Arbiter.create()

 
