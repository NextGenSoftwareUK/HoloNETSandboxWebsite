# HoloNET Sandbox (website)

The page at [sandbox.holonet.oasisomniverse.one](https://sandbox.holonet.oasisomniverse.one): try HoloNET in a browser. It is a single static file, `index.html`.

It calls the **sandbox service**, a small ASP.NET Core app that runs HoloNET against a Holochain conductor. The service is in
[`sandbox/`](https://github.com/holochain-open-dev/holochain-client-csharp/tree/main/sandbox) in the HoloNET repository; the same page is served by the service itself when you run it locally,
so `index.html` here is a copy of `sandbox/HoloNET.Sandbox/wwwroot/index.html`. Change it there, then copy it here.

Hosted at `https://api.sandbox.holonet.oasisomniverse.one` by default. The page's "Backend settings" can point it at your own service.
