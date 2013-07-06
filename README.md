Aunven
======

Check it, this is a ridiculous attempt at providing some custom datas to PCGen. Ryan's got this setting called Aunven that's calling for us to redefine some of the stuff provided in the OGL Pathfinder library.

This README is geared at OS X. If someone does Windows stuff, please instructions below.

Making it Work
---------------

    Install PCGen. From the website. You don't need my help for that.
    Pop open the terminal. Do this:
    $ cd /Applications/PCGen\ 6.00.1.app/Contents/Resources/Java/data/homebrew/
    $ git clone git@github.com:jnf/Aunven.git
    Now go make a drink. That was the easy part.

Ok, so now you have to tell PCGen to load our Aunven data alongside the other Pathfinder materials. The interface is kinda clunks, but, if you do it right, you should only ever have to do it once. So, fire up PCGEn and. . .

    After the UI initializes, pop over to the _Advanced_ tab of the *Select Sources* window.
    Pop open the *Homebrew* dropdown and select _Aunven_ from the list.
    Then use the same process to track down whatever other sources you're using.
    Then press *Add Selected*. It should then appear in the list on the right.
    Check the *Always use advanced sources* checkbox in the lower left of the window.
    Then, next to it, click *Save Source Selection*. It'll make you save stuff. Neat, eh?
    Finally, click *Load*.

That's it, prolly. Unless something's gone wrong. If you open a pre-existing character, you'll get a prompt to update or whatevs. Once you've done that, Aunven data should be available for your use. Yay.

Something gone wrong?
---------

Sorry, bro. Delete the repo, I guess. We'll get better at this, probably. Oh, I probably should have told you to backup your characters first.