Sinatra en OpenShift
====================

Este repositorio de git le ayudará a ponerse en marcha rápidamente Sinatra en OpenShift. 


Crear proyecto en OpenShift
----------------------------

Crear una cuenta en https://www.openshift.com

Su creacion y configuración en ubuntu esta explicada en mi blog, en el post http://www.eldeveloperblog.tk/?p=13 

Crear una aplicación de ruby

    rhc app create sinatra ruby-1.9 --from-code https://github.com/julianjjo/Sinatra_openshift.git

Eso esta todo listo, ahora lo puede ver en:

    http://sinatra-namespace.rhcloud.com

