# paratext-integration
API integration with ParaTExt

## ParaTExt
[ParaTExt](https://pt8.paratext.org/) is world’s most popular Bible translation tool and is being used by 1000s of Bible translators across the world. It is developed jointly by United Bible Societies and Summer Institute of Linguistics.  Being a very feature rich and mature application, it is offers a lot of cool tools to help translators in doing effective translation.

Since ParaTExt version 8, it offers an API to access some of these tools. paratext-integration is an application written in Python using Flask that can interact with ParaTExt. The API is not yet production ready, but it should be stable enough for testing.

The [API documentation](https://data-access-dev.paratext.org/) gives a fairly detailed infomation of accessing the API using JS. ParaTExt API uses JWT for authentication and the same can be generated using a valid ParaTExt user registration. [ParaTExt Registration](https://registry.paratext.org/) can be done here. 

