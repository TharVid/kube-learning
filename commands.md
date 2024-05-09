<!DOCTYPE html>
<html>
<head>
    <title>Kubernetes Rolling Update Guide</title>
</head>
<body>

    <h1>Kubernetes Rolling Update Guide</h1>

    <h2>Create Namespace</h2>
    <p>Create a new namespace:</p>
    <pre><code>kubectl create namespace prod</code></pre>

    <hr>

    <h2>Rolling Update</h2>
    <p>Update the deployment to use the new image version:</p>
    <pre><code>kubectl set image deployment/nginx-deployment nginx-container=nginx:1.17</code></pre>

</body>
</html>
