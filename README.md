# Easyweb.site plain example template

Simple and plain .NET 6 starting template for creating content using Easyweb CMS and ew-tag-pack.

1. If you haven't created an Easyweb account yet, sign up at https://app.easyweb.se/account/createaccount

2. If you haven't created a site to fetch content from yet, once signed in, create a new site @ My account -> My sites -> New site (plus sign)

3. Once you have an account and a site, enable your API-key by clicking the cloud in the top bar and creating a new API-key. Copy the OAuth2 API-credentals to appSettings.json -> ApiSettings where the values are marked with x's. Replace DataOptions/UnionId/"xxxx" with your 4 digit union-/site id (seen in the end of your endpointRoot, ``/extapi/[here]``). 

4. Run teh app to make sure your connection is up running and working

5. Start building using the studio in Easyweb and the tag helpers provided by the Easyweb.site-packages, such as:

``<ew-template for-key="[key]" />``

``<div ew-list="[key]">More content...</div>``

``<span ew-for="[key]"></span>``

6. Read and learn more at https://www.easyweb.site
