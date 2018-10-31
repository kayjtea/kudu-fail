1. Create Azure App Service, generic "Web App"
2. In app settings, set WEBSITE_NODE_DEFAULT_VERSION to 6.9.1 (should be the default)
3. In Deployment Center, choose "Local Git", "Kudu Build Provider"
4. Push to URL; watch the console -- it will fail trying to install rimraf
