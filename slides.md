
# Effective Documentation

<http://preaction.github.io/Effective-Documentation/>

How to write effective docs efficiently

by [Doug Bell (preaction)](http://preaction.me)  
<a href="http://twitter.com/preaction"><i class="fa fa-twitter"></i> @preaction</a> |
<a href="http://github.com/preaction"><i class="fa fa-github"></i> preaction</a> |
[Chicago.PM](http://chicago.pm.org)

Source: <https://github.com/preaction/Effective-Documentation>  
License: [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)

------

# New Developer

---

# Hi

Welcome to the team!

------

# Questions

---

# Code: How

---

# Tests: What

---

# Docs: Why

------

# Why Is The Key

---

# Improving

---

# Refactoring

---

# Revitalizing

------

# Code Without Why is Technical Debt

------

# XXX

------

Communication requires an

# Audience

---

# Experienced Devs

Docs by you for you

---

# New Devs

They've got questions..
Docs have answers

---

# Users

Code can't help them

------

# Required Docs

------

# Abstract

---

# Quick Description

---

# One line

TL;DR

---

# Am I in the right file?

---

# Goes on top

------

# Description

---

# Overview of this file

---

# Where it fits in the project

---

# Paragraphs

---

# What I need to understand this file

---

# Terms and definitions

---

# Goes on top

-------

# Synopsis

---

# Code example

---

# What real usage looks like

A picture is worth a thousand words

---

# Goes on top

------

# See Also

---

# Related information

---

# Where to go next

---

# Where to go first

---

# Well-Linked Docs

---

# Goes on top

------

# Top of File

Above the fold

---

```
package My::Module;
# ABSTRACT: This is what my module does

=head1 SYNOPSIS

    # How to use My::Module

=head1 DESCRIPTION

What My::Module does, and how it fits into the project

=head1 SEE ALSO

Other topics related to My::Module
```

---

# For Users

Answer the basic "Why"

---

# For New Devs

Open file, immediately see docs

---

# Experienced Devs

Already know what to search for

------

# Methods

Attributes and Other

---

# Same as Before

---

# Name

`=head2 Method Name`

---

# Synopsis

```
my $status = $obj->method_name( $arg, @more );
```

---

# Description

---

# See Also

---

```
=head2 my_method

    my $retval = $object->my_method( $arg, @more );

This method is my method, and not yours. C<$arg> is
an arguemnt. @more is more arguments, optional. It
returns a scalar retval.

This method is used to X and Y but not Z. If you want Z
go down the hall to Abuse.

=cut

sub my_method { ... }
```

---

# Goes above the method

------

# Don't

------

# Docs At The Bottom

---

# Hidden From Users

---

# Out of Sight, Out of Mind

Out of Date

------

# Alphabetize

---

# Anti-narrative

---

# Read This Book

In Alphabetical Order

---

a a a?" a a a a a, a a a a a a a a a a A a, "a A a a a a."
a A a a a a a a a a a. A a A a a a a a a a A a A a a,
a a a a a a a a a a a a. a a a a a a a a a a a a a a a a a a a a,
a a a a a a a a a a a a a a.
a a a a a, a a a a a a a a. a a a a a a a a A a a a a a 'a-a' a a a.
"a, a a a a a a a, a a a a a a A a a a a a a a a A a a A a a a a. a,
a a a a, a a a a. a a a a a, a a,
a a a a a a - a a A a a - a a a a a a a A a a, a a a a a. a a-a
a a a a a a a a a 'a-a a' a."
a a a a. a a a a a a a a A a a a a a a a a a a a 'a-a' a a a a a a. a a,
a a, a a a a. a a a a a a a a a-a a a a a a a a. a, a a, a a a.
a a a, a a a a a a a a a, a a a a a a a a a a a a a a A a A A,
a a a a a a a. a a a a a a a a a a a a a a A a a a a A a a a a 'a a' a.
a a a A a a a a a a a a a.\*

<http://www.starshiptitanic.com/novel/page01.html>

---

# Just in case

Yoz's Original Collapsible Travelling Punctuation-In-Place-Alphabetiser
(PIPA)

```
print grep(s/\w+([\.']\w+)*/shift(@w)/ge||$_,
grep(s/\w+([\.']\w+)*/(push(@w,$&),$&)[1]/ge||$_,
<>),do {@w=sort {lc($a) cmp lc($b)} @w;''});
```

------

# Don't D.R.Y.

---

# Docs can Repeat

---

# Methods have Assumptions

---

# Link to them

Good solution

---

# Repeat them

Better solution

---

# Link and Repeat

Best solution

------

# Summary

---

# Docs Answer Why

---

# Why Is the Key

---

# Make them Useful

Remember your Audiences

---

# Easy to Find

------

# Questions?

------

# Thank You!

