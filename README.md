# Docker image to redirect http to https

The reasoning for this is quite simple, if you just want to redirect all traffic, you can run this container on say port 80.  Then on another port, you run your application.  You point all of the traffic on HTTP on your load balancer to this container. And the HTTPS traffic to your app.

