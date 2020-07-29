# YARR

Let's say, for the sake of argument, that you were running a VMS Hobbyist
License.  And let's say that you had a working license file (in the
form of a DCL script).  But let's also say, it's expiring, or expired,
and you're concerned that even if you get HPE to renew it in 2020, it's
going to expire at the end of 2021, and you want to keep running on
VAX, or you want to run a pre-VSI version on Alpha.

Thanks, by the way, to VMS Software, Inc. for continung the hobbyist
program for Alpha, Itanium, and, eventually x86.

Let's further stipulate that somehow you managed to get hold of the C
program pakgen and build it, so you had the ability to generate non-
expiring licenses for your DEC licensed software.

Then in that case, if you were a sort who didn't care much about niceties,
you might want to run this to generate a DCL script that would replace your
time-limited licenses with non-expiring ones.

Of course you shouldn't execute the resulting script, with privileges
enabled, on a VMS system, because that'd be wrong.  Oh so very wrong.

This code is in the public domain.
