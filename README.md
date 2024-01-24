Add a file called "config.h" beside Telegraph.xcodeproj and place this code in that:

    #define SETUP_API_ID(apiId) apiId = YOUR_API_ID;
    #define SETUP_API_HASH(apiHash) apiHash = YOUR_API_HASH;
