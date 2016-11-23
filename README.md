# Study Guide

## Implementing Microsoft Azure Infrastructure Solutions - 70-533

###  **Design and implement Azure App Service Apps (15-20%)**

1. **Deploy Web Apps** 
   * Define deployment slots,Roll back deployments ([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-staged-publishing))
   * Implement pre- and postdeployment actions ([LINK1](https://github.com/projectkudu/kudu/wiki/Post-Deployment-Action-Hooks))
   * Create, configure, and deploy packages; ([LINK1](https://www.iis.net/learn/publish/using-web-deploy/introduction-to-web-deploy),[LINK2](https://docs.microsoft.com/en-us/azure/vs-azure-tools-publishing-using-powershell-scripts))
   * Create App Service plans ([LINK1](https://docs.microsoft.com/en-us/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview)) 
   * Migrate Web Apps between App Service plans ([LINK1](http://stackoverflow.com/questions/23685094/is-it-possible-to-move-a-website-to-a-different-web-hosting-plan)) 
   * Create a Web App within an App Service plan

2. **Configure Web Apps**
   * Define and use app settings, connection strings, handlers, and virtual
     directories([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-configure)); 
   * Configure certificates and custom domains ([link1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-configure-ssl-certificate),[link2](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-purchase-ssl-web-site)); 
   * Configure SSL bindings and runtime configurations; 
   * Manage Web Apps by using Azure PowerShell and Xplat-CLI

3. **Configure diagnostics, monitoring, and analytics**
   * Retrieve diagnostics data; view streaming logs; 
   * Configure endpoint monitoring; 
   * Configure alerts; configure diagnostics; 
   * Use remote debugging;
   * Monitor Web App resources

4. **Configure Web Apps for scale and resilience**
   * Configure auto-scale using built-in and custom schedules; 
   * Configure by metric; 
   * Change the size of an instance; 
   * Configure Traffic Manager

*Miscellaneous*
  
  [Best Practises](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-best-practices)