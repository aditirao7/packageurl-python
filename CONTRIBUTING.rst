============
Contributing
============

Contributions are welcome and appreciated!
Every little bit helps, and credit will always be given.

When contributing to purl (such as code, bugs, documentation, etc.) you
agree to the Developer Certificate of Origin http://developercertificate.org/
and its license (see the mit.LICENSE file).  The same approach is used
by the Linux Kernel developers and several other projects.

Before committing, add the following line to the pre-commit.sample file in the .git/hooks directory::

    black -l 100 . 
    
Now rename the file to pre-commit by removing the .sample extension.

For commits, it is best to simply add a line like this to your commit message,
with your name and email::

    Signed-off-by: Jane Doe <developer@example.com>

Please try to write a good commit message.
See https://chris.beams.io/posts/git-commit/
