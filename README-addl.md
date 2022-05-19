# About

This is a variation, of a portion, of the https://github.com/SocialiteProviders/Providers project. Specifically, this patches an issue I was having in my build, likely due to still being on PHP 7.3 and the version bump to 7.4 required in a later version, with the `microsoft-azure` Socialite provider. This simply patches in the apparently required `grant_type` variable into the token requests.

The original readme for this project can be found here - [Original README](./README.md)  
  
The license for the overarching project that this project is a smaller portion of is found here - [Original LICENSE](./LICENSE)