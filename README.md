# SponzaRepack
forking https://github.com/jimmiebergmann/Sponza, reencode as png, prep for use as array textures

Basically, for array textures, I want to be able to index into a set of identically sized textures. There is a third component to my texcoords, that are used to index into the array. The non-square textures are a pain in the ass, so I went ahead and squared them. Normalized texture coordinates hold, so nothing changes by using them that way. It's just a bit more data to pass to the GPU, and only a two textures need it ( for the chains ).
