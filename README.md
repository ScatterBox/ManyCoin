=======
ManyCoin
=======

Key stats:

Project started in late March, 2014.  

10240 coin initial payout - since its a power of 2, it will halve nicely! 

2 year half life - get in early.  Besides... will anyone really be wanting to mine decades from now?

23.5 years of coin generation (yields roughly 100X the 84M Litecoin limit)

1 minute block time - should be a decent compromise

    Short form: Faster transaction, but no so fast that stale blocks become a huge problem 
    Long form: http://bitcoinmagazine.com/8972/quarkcoin-noble-intentions-wrong-approach/ 

25 hour block difficulty adjustment (every 1000 blocks)
    
Like Litecoin, manycoin is scrypt based - a mild manored attempt at keeping it in mortal hands while still using commonly available mining tools.

Unlike Litecoin, manycoin uses the Kimoto Gravity Well difficulty adjustment to provide some protection from difficulty surges.

Hard numbers:

30,000,000,000	Total coins in the pool

1.5 * 60 * 1000	TargetTimespan (e.g. 25 hours)

60 Second	TargetSpacing (e.g. 1 minute)

Ports:

Listen:   33888 (8334 for testnet)

JSON-RPC: 33887 (7332 for testnet)

License
-------

manycoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.


Credits
--------

Obviously, primary credit has to go to the Bitcoin and Litecoin development teams without whome this project would never have been conceived of.  The wallet code was cloned from the 0.8.6.2 release of Litecoin.

Addition credits go to the links below:

http://devtome.com/doku.php?id=scrypt_altcoin_cloning_guide
https://bitcointalk.org/index.php?topic=149479.0

And all the folks responsible for QT, MingW32, and the other tools used to build the Windows version of this.

Development of ManyCoin was done using a Gentoo Linux environment.

Special thanks to the folks over at http://multicoin.zapto.org:8080/ for their support

Donations
----------


