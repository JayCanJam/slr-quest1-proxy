# slr-quest1-proxy
VR Streaming Proxy for a popular service

If you found this project, you're clearly looking for a solution for continued DeoVR Streaming on the Quest1 Device.

My goal, should this project be successful, is to develop an HTTP Proxy that has enough internal logic to fix whatever the hell broke with the upstream service in mid-September, 2024, where they threw their hands up in the air and said Quest1 deprecated and broken. (Nice of them to do that just days before Quest3 announced rolling out, huh?)

### First Steps ###
Try to capture traffic, ideally with an injected SSL/TLS certificate to the VR Headset for the proxy service so we can peek into the internal traffic. This is a non-starter if we can't even get past this step.

