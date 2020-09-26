ProductCatalogApi: Api web site
ProductCatalogDaemon: Console app calls api site with appRoles (application permissions). Deamon apps implement the client credentials flow. 
ProductCatalogWeb: MVC site calls api site with OAuth 2.0 authorization code grant flow (delegate permission)
Tutorial: https://docs.microsoft.com/en-us/learn/modules/identity-secure-custom-api/