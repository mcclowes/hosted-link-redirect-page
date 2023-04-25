# hosted-link-redirect-page

Once your customers have successfully completed authorization of the connection to their data via Link, you can redirect them to another website.

There are a few ways you can redirect your customers:

- Redirect to a static URL
- Redirect with reserved query parameters
- Redirect with custom query parameters

[Read more about redirects](https://docs.codat.io/auth-flow/customize/set-up-redirects)...

Example redirect URL setting:

```https://hosted-link-redirect-page.vercel.app/{companyId}?flow=Copay&clientId={clientId}&connectionId={connectionId}&companyId={companyId}&integrationId={integrationId}&sourceId={sourceId}&platform={platform}&platformName={platformName}&sourceType={sourceType}&statusCode={statusCode}&errorMessage={errorMessage}&statusText={statusText}```


Resolves to:

```https://hosted-link-redirect-page.vercel.app/c0d83fa2-bfc6-4d8e-a39d-276051ad48df?flow=Copay&clientId=042399f5-d104-4f38-9ce8-cac3524f4e88&connectionId=f3c45050-1827-4223-840c-a4a85792ab66&companyId=c0d83fa2-bfc6-4d8e-a39d-276051ad48df&integrationId=9e0cc03b-3868-4543-98c0-568f0f1b12a3&sourceId=aff0f057-255f-42c4-8d4a-ae23b43e1615&platform=mqjo&platformName=Sandbox&sourceType=Accounting&statusCode=200&errorMessage=&statusText=```