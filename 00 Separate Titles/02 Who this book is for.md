# Who this book is for

TODO: Provide a recommended way of reading for every category.

This book is written by a software engineer
for software engineers in a broad sense,
i.e. both “dev” and “ops” ends of traditional division are covered.
The modern trends in the software industry
are inclined towards erasing the line between these two,
manifesting new ideas in such approaches as Platform Engineering (links).

Despite being inhabited mostly by technology-infatuated people,
Nix might be useful for a wider audience.
Though the book might be used by inquisitive people
who don’t consider themselves software engineers
but just want to leverage Nix as a package management tool
or learn some basics of software deployment,
this usage comes in limited form.

The main limitation comes from the fact that
I decided to exclude NixOS as a substantive topic
to keep the size of the book reasonable.
At the same time, Nix/NixOS users might be interested in
chapters devoted to the Nix package manager
and the NixOS module system.

Accordingly, I tried to keep bearing in mind the
following kinds of potential readers.

* Just *curious people*, who want to know
what problems software deployment faces in the wild
and how those might be solved with Nix.
They might have very little knowledge of software development,
be any OS users,
including systems that are not supported by Nix.

* *Linux/macOS users*,
who consider using Nix
as their primary or additional package manager
or switching to NixOS.
They also might want to be able to install any software
from a GitHub repository that provides a Nix flake.

* Software developers, who *don't want to learn Nix*,
but are willing to understand it and use it in their work
for building development environments, build and deploy the stuff
they are working on.
Generally, they don't want to write any Nix code,
probably just modify it occasionally.
This is a broad category and it needs further qualification.
Some might be familiar with functional languages
and be comfortable with the connected notions
like immutability, purity, side effects and laziness.
Others might come from the imperative programming world.
Among these, there might be those
who are willing to learn some ideas from functional programming
and those who tend to be reluctant for some reason.

* Software developers and DevOps folks, who want to learn Nix,
including Nix language, become proficient in Nix
and use it in their daily work. This