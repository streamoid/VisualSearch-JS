**VisualSearch-JS**
===================

Using **VisualSearch-JS** SDK fashion websites can add visual search feature seamlessly into their website

**What is Visual search in fashion:**

Any fashion apparel/accessory that inspires an end-user, for example, that perfect summer dress he/she saw in a magazine or those shoes that the woman was wearing at the coffee shop, User can just take a photo and find products visually similar to those in your 'fashion website' using **VisualSearch-JS** SDK.

**Integration**

1) Adding script in **head** tag

```
(function(i,s,o,g,r,t,k,a,m){
         i['PiqitObject']=r;i['PiqitGa']=t;i['PiqitToken'] = k;i[r]=i[r]||function() {
         (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
         m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
         })(window, document, 'script', 'LOADER-URL', 'PQT', 'GA TRACKER-ID', 'CLIENT TOKEN');
```     

Add the below line of code(div) in your html source code wherever you want to see the visual search button. A search button will be automatically added in your website.

```
 <div class="streamoid_sdk streamoid-visualSearch-button" data-token="CLIENT TOKEN" data-service="visualSearch" data-function="initialize"></div>
 ```
 
Please contact streamoid.support@streamoid.com to get your LOADER-URL, CLIENT TOKEN, GA TRACKER-ID

**User Flow**

The below screenshots depicts user flow for Visual search feature
1) Visual search button
![](screenshots/visual_search_1.png)

2) Uploading an image
![](screenshots/visual_search_2.png)

![](screenshots/visual_search_3.png)

3) Results screen
![](screenshots/visual_search_4.png)

![](screenshots/visual_search_5.png)

