# Study Guide

## Implementing Microsoft Azure Infrastructure Solutions - 70-533

###  **Create and manage Azure Resource Manager virtual machines (20-25%)**

1. **Deploy workloads on Azure Resource Manager (ARM) virtual machines (VMs)** 
   * Define deployment slots,Roll back deployments ([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-staged-publishing))
   * Implement pre- and postdeployment actions ([LINK1](https://github.com/projectkudu/kudu/wiki/Post-Deployment-Action-Hooks))
   * Create, configure, and deploy packages; ([LINK1](https://www.iis.net/learn/publish/using-web-deploy/introduction-to-web-deploy),[LINK2](https://docs.microsoft.com/en-us/azure/vs-azure-tools-publishing-using-powershell-scripts))
   * Create App Service plans ([LINK1](https://docs.microsoft.com/en-us/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview)) 
   * Migrate Web Apps between App Service plans ([LINK1](http://stackoverflow.com/questions/23685094/is-it-possible-to-move-a-website-to-a-different-web-hosting-plan)) 
   * Create a Web App within an App Service plan

2. **Perform configuration management**
   * Define and use app settings, connection strings, handlers, and virtual
     directories([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-configure)); 
   * Configure certificates and custom domains ([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-configure-ssl-certificate),[LINK2](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-purchase-ssl-web-site)); 
   * Configure SSL bindings and runtime configurations; 
   * Manage Web Apps by using Azure PowerShell and Xplat-CLI ([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-app-azure-resource-manager-xplat-cli),[LINK2](https://channel9.msdn.com/Series/Windows-Azure-Web-Sites-Tutorials/Managing-Windows-Azure-Web-Sites-with-PowerShell))

3. **Design and implement VM storage**
   * Retrieve diagnostics data; view streaming logs([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-enable-diagnostic-log)); 
   * Configure endpoint monitoring([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-monitor),[LINK2](https://docs.microsoft.com/en-us/azure/application-insights/app-insights-monitor-web-app-availability)); 
   * Configure alerts; configure diagnostics([LINK1](https://docs.microsoft.com/en-us/azure/application-insights/app-insights-alerts),[LINK2](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-enable-diagnostic-log)); 
   * Use remote debugging([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-dotnet-troubleshoot-visual-studio#a-nameremotedebugaremote-debugging-web-apps));
   * Monitor Web App resources

4. **Monitor ARM VMs**
   * Configure auto-scale using built-in and custom schedules([LINK1](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/insights-how-to-scale),[LINK2](https://docs.microsoft.com/en-us/azure/app-service/app-service-environment-auto-scale),[LINK3](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-scale-a-web-app-in-an-app-service-environment)); 
   * Configure by metric; 
   * Change the size of an instance([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-scale); 
   * Configure Traffic Manager([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-traffic-manager))

5. **Manage ARM VM availability**
   * Configure auto-scale using built-in and custom schedules([LINK1](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/insights-how-to-scale),[LINK2](https://docs.microsoft.com/en-us/azure/app-service/app-service-environment-auto-scale),[LINK3](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-scale-a-web-app-in-an-app-service-environment)); 
   * Configure by metric; 
   * Change the size of an instance([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-scale); 
   * Configure Traffic Manager([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-traffic-manager))

5. **Scale ARM VMs**
   * Configure auto-scale using built-in and custom schedules([LINK1](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/insights-how-to-scale),[LINK2](https://docs.microsoft.com/en-us/azure/app-service/app-service-environment-auto-scale),[LINK3](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-scale-a-web-app-in-an-app-service-environment)); 
   * Configure by metric; 
   * Change the size of an instance([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-scale); 
   * Configure Traffic Manager([LINK1](https://docs.microsoft.com/en-us/azure/app-service-web/web-sites-traffic-manager))

*Miscellaneous*
  
  [Best Practises](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-best-practices)