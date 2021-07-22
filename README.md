[![New Relic Experimental header](https://github.com/newrelic/opensource-website/raw/master/src/images/categories/Experimental.png)](https://opensource.newrelic.com/oss-category/#new-relic-experimental)

# New Relic .Net Agent Instrumentation for Azure CosmosDB DocumentClient

This New Relic .Net agent instrumentation package provides instrumentation for Azure CosmosDB DocumentClient class. API calls made by the clients to MS Azure CosmosDB's DocumentDB database are captured as database calls in New Relic.


## Installation

1. Drop the extension dll in the newrelic agent's Program Files "extensions" folder.

```cmd
   copy Custom.Providers.Wrapper.DocumentDb.dll C:\Program Files\New Relic\.NET Agent\netframework\Extensions
```

2. Drop the extension xml in the newrelic agent ProgramData "extensions" folder.

```cmd
   copy Custom.Providers.Wrapper.DocumentClient.xml C:\ProgramData\New Relic\.NET Agent\netframework\Extensions
```

***
**Note: The XML file must be dropped into ProgramData's extension folder whereas DLL file must be dropped into Program Files's extension folder**
***

3. Restart your application after adding the extension files and configurations.

4. Check your results in New Relic UI.


## Support

New Relic has open-sourced this project. This project is provided AS-IS WITHOUT WARRANTY OR DEDICATED SUPPORT. Issues and contributions should be reported to the project here on GitHub.

We encourage you to bring your experiences and questions to the [Explorers Hub](https://discuss.newrelic.com) where our community members collaborate on solutions and new ideas.


## Contributing

We encourage your contributions to improve [Project Name]! Keep in mind when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project. If you have any questions, or to execute our corporate CLA, required if your contribution is on behalf of a company, please drop us an email at opensource@newrelic.com.

**A note about vulnerabilities**

As noted in our [security policy](../../security/policy), New Relic is committed to the privacy and security of our customers and their data. We believe that providing coordinated disclosure by security researchers and engaging with the security community are important means to achieve our security goals.

If you believe you have found a security vulnerability in this project or any of New Relic's products or websites, we welcome and greatly appreciate you reporting it to New Relic through [HackerOne](https://hackerone.com/newrelic).

## License

New Relic .Net Agent Instrumentation for Azure CosmosDB DocumentClient is licensed under the [Apache 2.0](http://apache.org/licenses/LICENSE-2.0.txt) License.

