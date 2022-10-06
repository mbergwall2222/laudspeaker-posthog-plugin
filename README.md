<p align="center"><a  href="https://laudspeaker.com/"><img  src="[https://user-images.githubusercontent.com/59817155/126267034-ae9870b7-9137-4f45-be65-d621b055a972.png](https://user-images.githubusercontent.com/7728266/194205572-82247172-915d-49d4-b698-ff26ba117e6b.png)"  alt="Laudspeaker - Open Source Customer Messaging Workflows"  height="50"/></a></p>


<p align="center"><b>Open source customer messaging and notification workflow software</b></p>

<br/>

  

#  Laudspeaker PostHog Plugin
<br>

  | **Send events from PostHog tos Laudspeaker** |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

  

Questions? Please join our [Slack channel](https://laudspeakerusers.slack.com/ssb/redirect) or visit our [site]((https://laudspeaker.com/)).

<br>

  
## Get Started

 - To experience the full power of laudspeaker we recommend you import your posthog users first via the event integration on laudspeakers application 
 -  Create a PostHog source in your [RudderStack dashboard](https://app.rudderstack.com/). Learn more about adding a source in RudderStack [here](https://docs.rudderstack.com/get-started/adding-source-and-destination-rudderstack).
   
 ![PH-init](https://github.com/rudderlabs/rudderstack-posthog-plugin/blob/master/images/PH-init.png)

 - After adding the source, it should look something like the following:

 ![PH-source](https://user-images.githubusercontent.com/59817155/109136455-2416f100-777e-11eb-83db-342bee7f119b.png)

 - Get the source `write-key` and your `RudderStack server URL` (also called the `Data Plane URL`).
 - Copy this repo URL.
 - Go to your PostHog dashboard, and add a custom plugin with this URL.

  ![PH-plugin](https://github.com/rudderlabs/rudderstack-posthog-plugin/blob/master/images/Screenshot%202021-02-22%20at%207.49.50%20PM.png)
  
 - Once added successfully, you will need to configure the RudderStack plugin with the source write key and RudderStack server URL that you copied above. The default RudderStack server URL is configured to https://hosted.rudderlabs.com/v1/batch. Append `v1/batch` to this URL.

 ![PH-plugin-config](https://github.com/rudderlabs/rudderstack-posthog-plugin/blob/master/images/Screenshot%202021-02-22%20at%207.50.55%20PM.png)

 - Finally, enable this plugin and you should start seeing events sent to your PostHog instance flowing to this RudderStack source.

  For more info on PostHog plugins, check [this](https://posthog.com/docs/plugins/overview).

## License

**RudderStack PostHog Plugin** is released under the [MIT License][mit_license].

## Contribute 

We would love to see you contribute to RudderStack. Get more information on how to contribute [here](CONTRIBUTING.md).

## Follow Us

-  [RudderStack Blog][rudderstack-blog]

-  [Slack][slack]

-  [Twitter][twitter]

-  [LinkedIn][linkedin]

-  [dev.to][devto]

-  [Medium][medium]

-  [YouTube][youtube]

-  [HackerNews][hackernews]

-  [Product Hunt][producthunt]

[slack]: https://resources.rudderstack.com/join-rudderstack-slack
[twitter]: https://twitter.com/rudderstack
[linkedin]: https://www.linkedin.com/company/rudderlabs/
[devto]: https://dev.to/rudderstack
[medium]: https://rudderstack.medium.com/
[youtube]: https://www.youtube.com/channel/UCgV-B77bV_-LOmKYHw8jvBw
[rudderstack-blog]: https://rudderstack.com/blog/
[hackernews]: https://news.ycombinator.com/item?id=21081756
[producthunt]: https://www.producthunt.com/posts/rudderstack
[agplv3_license]: https://www.gnu.org/licenses/agpl-3.0-standalone.html
[sspl_license]: https://www.mongodb.com/licensing/server-side-public-license
[mit_license]: https://opensource.org/licenses/MIT
[config-generator]: https://github.com/rudderlabs/config-generator
[config-generator-section]: https://github.com/rudderlabs/rudder-server/blob/master/README.md#rudderstack-config-generator
[rudder-logo]: https://repository-images.githubusercontent.com/197743848/b352c900-dbc8-11e9-9d45-4deb9274101f
