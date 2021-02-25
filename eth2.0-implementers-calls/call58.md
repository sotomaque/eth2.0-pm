**danny** so yesterday evening i wrote down the high level things that happened with hard fork 1. We are still scrambling to get a pre-release done. We want at least all the consensus items in place and theres still some ongoing work there (that initial prerelease so that test vectors can be worked on iteratively). High level items are: get these prerelease and vectors out. iterate on prereleases there if necessary based on client feedback. then do a full prerelease which has all of the networking and validating. at that point things are done enough so that people can work on test nets and we can iterate if theres additional feeback. from there we can do something similar to what we did with the mainnet launch. i expect private, transient, single client test nets likely testing just hardfork 1 features from genesis and then testing forking the net partially through. then we will begin collaborating with eachother. doing some private transient multi-client test nets, doing same sequence of events, testing in isolation, and then testing through a forking mechanism. those we might spin one out to be public or semi public. but piermont or whatever is piermont will serve as our public testnet. and so after we have gone through all those, after we have done as many pre releases as necessary, we will do a mainnet release that will include a fork epoch chosen for piermont and mainnet, and we will yell at everyone to update their nodes. no big suprises in this list, i just wanted to write it down, and we will iterate and expand on it. behind that theres a link to a lot of ongoing work that many people on my team are working on, which is working on geting last features written and tested and a number of other things like fork tests, actually like fork epoch tests as well as fork choice tests, which choy is working on. so theres a lot of activity there, i thought we would get a prerelease by about today, and we are not, i appologize but we are on it. any thoughts or questions on any of that?

**ben** do you have any updates on what timing you have in mind for said, kind of mid-year?

**danny** the target would be june, but i dont want to put an exact date on it until we get pre-releases out. all that said, I want yall to make the decision based off of the work as it comes it, and your understanding of the work at hand, we can make the decision there. There is a Eth1 fork in april, and theres an Eth1 fork that will happen very likely by the end of July, due to the difficulty bomb. so its probably best if we dont do it right at the same time, staggared a bit. It is also best if we have this process done by the time London is done in July so that we can put the metal to metal on some collaborative work. Thats kind of the thinking there.

**ben** sounds good as a planning goal so that helps plan. thanks.

**danny** okay, anything else on that? i know that we are the biggest bottleneck right now and we are putting a lot of work in so we will unblock soon. 

**jacek** I think maybe one interesting thing about hardfork 1 is to use that as a kind of date for when we have to support thinking, not from Genesis.

**danny** yeah, absolutley

**jacek** becauase i think clients now if you look at 1.0, event if clients were to release, even if all clients release app syncing from genesis, starting today, we kind of still have to support all 1.0 clients that we released previously and not force them upgrade

**danny** yeah thats a good point, to sort of change some of the networking descriptions

**jacek** so hardfork 1 is a good spot to change those essentially

**danny** I very much agree, maybe we should spend a little bit of time pondering if there is any other coordination points that we should slip in there. For example, not that theres anything to do 