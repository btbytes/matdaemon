matdaemon
=========

matdaemon powers MatDaemon.com - Plots as a Service. Powered by Matplotlib, Tornado and MongoDB.

## What's up?

[Matplotlib](http://matplotlib.sourceforge.net) is a kick-ass plotting library that has more plots 
than you can shake a stick at. 

## But..

(There is always a but.)

Using Matplotlib in a hurry (or in anger) is not always easy. 

  * Installing matplotlib is not for the faint of heart. `numpy` anyone?
  * The library is not obvious. Why a "show()"?

Apart from the small niggles, there are some features that we really use on the web:

  * Can I name a 'style' of chart and reuse it again?
  * Maybe I can share the chart type with others and let them use it with their own data.
  * Can I have this chart in `.png` and `.pdf`?
  * Can I have an API using which I can generate plots dynamically?
  * Can I cache these plots so that I can embed them in a webpage to show stats etc?

The goal of MatDaemon.com is to do be able to all this over time.

### Tech

  * Matplotlib -- Duh! (for generating plots)
  * Tornado -- web application

This application will be built as a WSGI web app. The app is likely to be deployed on Redhat's [OpenShift](http://openshift.redhat.com) 
PaaS cloud.


### License

I have not decided on a license yet, but it is likely to be a permissive Open Source license.
