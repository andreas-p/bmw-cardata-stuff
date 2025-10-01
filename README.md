# bmw-cardata-stuff
BMW CarData related information

There are quite some problems around BMW CarData, and there's no central place where to communicate issues around. BMW's communication appears ... non-sufficient, so I created this repo to bundle issues for the CarData user community.

## Official BMW resources

### CarData portal
After registering a BMW/Mini car into the official website, the CarData is available. Here, you should be able to register a new `CarData Client`. This can be enabled for API and/or Streaming.

### OpenAPI spec for Device Code Flow and CarData itself

https://bmw-cardata.bmwgroup.com/customer/public/api-specification

### Integration guide

https://bmw-cardata.bmwgroup.com/customer/public/api-documentation

## Community Resources

### Streaming
@whi-tw has created a [POC project](https://github.com/whi-tw/bmw-cardata-streaming-poc) which implements a functional streaming client library, a command line tool and a simple gui server. This is an excellent start for own streaming implementations.

### API

A work-in-progress implementation with streaming and api calling combined can be found here https://github.com/JjyKsi/bmw-cardata-ha . There's also quite some discussion of issues there.

### Authentication
@whi-tw also wrote an excellent documentation about [authentication workflow](https://github.com/whi-tw/bmw-cardata-streaming-poc/blob/main/AUTHENTICATION.md) which is a lot more specific than the official integration guide.


## Maintenance of this project

I'm doing this only sporadically, this project should better be owned and fed by some BMW employee.

Use issues to communicate the problems to the community, but don't expect anything from me.
