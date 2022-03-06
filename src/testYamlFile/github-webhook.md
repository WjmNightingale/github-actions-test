Webhooks allow you to build or set up integrations, such as GitHub Apps or OAuth Apps, which subscribe to certain events on GitHub.com. When one of those events is triggered, we'll send a HTTP POST payload to the webhook's configured URL. Webhooks can be used to update an external issue tracker, trigger CI builds, update a backup mirror, or even deploy to your production server. You're only limited by your imagination.

webhook 允许你构建或设置集成，比如 GitHub 应用程序或 OAuth 应用程序，它们在 GitHub.com 上订阅特定的事件。当其中一个事件被触发时，我们将发送一个 HTTP POST 有效负载到 webhook 配置的 URL。webhook 可以用于更新外部问题跟踪器、触发 CI 构建、更新备份镜像，甚至部署到生产服务器上。你只是被你的想象力所限制。

Wwbhooks can be installed on an organization,a speciffic repository, or a Github App.Once installed, the webhook will be sent each time one or more
subscribed events occurs.You can create up to 20 webhooks for each event on each installtion target(speciffic organization or speciffic repository)
