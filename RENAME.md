<h3>Example Application</h3>

<pre>kubectl run nginx --image=nginx:1.9.12

kubectl expose rc nginx --port=80 --type=NodePort

kubectl describe svc nginx</pre>
