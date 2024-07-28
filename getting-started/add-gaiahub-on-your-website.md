# Add GaiaHub on your website

After creating your Chatbot, you might want to share it on your website, and here is how you do that:

In the app editor area, you'll find a sharing icon like in the picture:

<figure><img src="../.gitbook/assets/Screenshot 2024-07-28 at 17.26.04.png" alt=""><figcaption><p>Share your app</p></figcaption></figure>

In there you'll find several options to integrate your app with other things, like a website for example:

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption><p>Share your app via javascript</p></figcaption></figure>

Then, click on the "copy" button:

<figure><img src="../.gitbook/assets/Screenshot 2024-07-28 at 17.35.00.png" alt=""><figcaption></figcaption></figure>

And finaly, inject that block of code in your website. Here, as an example, we'll add it to our "Hello world!" page:

````
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello World Website</title>
</head>


<script type="module">
    import Chatbot from "https://gaiahub.github.io/web-packages/gaia-embed/dist/web.js"
    Chatbot.init({
        chatflowid: "a9ad179d-6ebd-4431-9042-ca05c78edc09",
        apiHost: "https://api.gaiahub.ai",
    })
</script>


<body>
    <h1>Hello World</h1>
</body>
</html>
```
````

And you will see a little floating chat button on the bottom of your website:



<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

\
\
But you also have other options:

* ReactJS
* Python
* cURL

You can pick up the option that best works for your use case.

Let us know if you need any help. Our team will be happy to help!

Happy hacking!

