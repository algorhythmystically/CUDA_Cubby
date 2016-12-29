# CUDA_Cubby

Parallel programming 

As most of us are aware, the world's data is getting fairly astronomical in volume. Because of this, programmers (like you, I imagine) have been seeking ways to handle it. I'm reminded of a story about a Chinese city that needed a 50 mile (they use a different metric, yi, I think) stretch of road built, and after hiring 100,000 people, were able to get it built in 1 (!) day. 

Parallel programming works in exactly that way by employing more processing units to simultaneously compute data, and it can compute problem sets in far less time than one might expect...by several (!!!) orders of magnitude. There are server farms right now running large scale programs utilizing this technology, and making the world a happier, healthier place by deciphering problems like: what will the weather be doing in 10 days, what will the biomolecular systems in your cell's plasma be doing 10ms from now, or even more perplexing, what is happening in the skies above us that might be monumentally important to know, you know? :)

This data is computed via the GPU, the graphics processing unit, because these days the GPUs in computers are so sophisticated (thanks to video games, yay Pong!) that they have enough computing power to manage what are called  'single precison' and 'double precision' floating point computations; single precision doing 32 bit (4-byte) memory addressing, and double precision being 64 bit (8-byte) memory addressing, and can do enough of them to make even the most Herculean CPU think about taking a cold shower before returning to the next event at the Decathalon. When I say memory addressing, I mean that the calculataions being done take up that much room in the GPUs 'cores', i.e. tiny transistor complexes in the GPU.

All that being said, perhaps the most vital issue regarding parallel processing is understanding not simply the technology, but how to actually use it effectively. I have found that a lot of explanations are laborious and difficult to plod through, and because I program in a fairly wide array of languages, I think it'll be useful to help everyone understand how to write good parallel code. Because a majority of my time programming has been spent in C++, I am initially focusing on sharing documents that facilitate implementing parallel processing in C++. I'm also focusing solely on NVidia's CUDA language, for no reason other than their documentation is more accessible, and ATI's GPU product line has less variety to choose from.

So, while I am going to end today with this little intro, in the near term I will be uploading files that have explanations of the various data types, functions, and other descriptive help on how to use CUDA, and also some files that I have written and am writing that are helpful as shortcuts or make using CUDA easier.

I hope you are all doing well, and thanks for spending a few minutes reading my little blurb. 

As E.T. says, be good.

Peace!



 
