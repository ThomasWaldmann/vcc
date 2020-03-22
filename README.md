VCC = Virtual Chaos Communication
=================================

Idea: simulate a chaos event (or also other, similar events) in cyberspace,
as far as possible.

Won't be the complete experience, but we could try how far we'll get.

Note: for now, we collect IDEAS here (see also issues for more details),
code might be elsewhere.


Experiences we get at such an event and how they could map
----------------------------------------------------------

there is some rough topic
- can be quite wide scope, as seen at CCC congress
- can be narrower scope, think of a Python Conference
- matter of planning / announcement (see "news room")

all participants publically meet at some big space at the same time.
- no space problem in the digital domain :)
- same time is a matter of planning / announcement.
- participants need to recognizably "be there". name / nick / photo?

  people obviously can't meet you if you're completely anonymous.

there is a map so you know where you can go.
- a digital map could just link to misc virtual rooms
- not limited to a fixed 2d/3d arrangement like a floor(s) map
- simple start: a list that can be filtered by tags or search expressions

there is a timetable "fahrplan" for events / talks / meetings / demos
- this is already digital
- simple start: a list sorted by time that can be filtered by tags / search expr.

official talks / demos / meetings
- live streaming with A/V, or just live audio + slides
- some channel for questions / discussion (chat, audio, A/V?)
- meeting: similar, just more interaction
- there could be also a linked "forum" for later

lightning talks
- same as above, time limit 5 or 10 mins

open space / self organized sessions
- same as above, but somehow kept or marked differently

limited spacetime
- each participant has only a limited amount of things they can watch
  or participate in.
- to not confuse people with too many offerings, i guess not only time
  (overall and per event) should be limited, but also space (amount of
  parallel offerings)

meeting friends
- you can't hug your friends and have meals with them, but:
- you still can meet them: if they are "there", they have time and comm
  channels are open (otherwise they would not be "there").
  audio, video, text, ...
- there can be public places to hang out (think of assemblies)
  - being there means one is open to publicly talk with some people about topic
  - 2 people start, more people can join listening or talking
  - how good does that work/scale with remote audio/video?
- if there is a need for private talk, a group of people could lock their
  conversation, so no more people can join and hear/contribute.
  (not sure this is needed, could be also just made outside of VCC)
- nice thing: your virtual person can be at multiple spaces at the same
  time. you can still only talk to a limited amount of people though.

DECT phones
- == some comm channel not bound to some specific space/room
- easy, just chat to someone
- should have "off" switch

artistic
- there could be rooms with nerdy music
- there could be rooms with visual arts

self.__doc__?
- some thing i always missed at such events is better "docs".
- you see a lot of nerds with computers, but often you don't see what they are
  working on (even if it is not at all intended to be secret or private).
- of course you can't talk to some thousand people and ask everybody, so a lot
  of interesting opportunities are likely lost.
- VCC could help here if people feed as much as they are comfortable with into
  the system. So people with common interests could better find each other.

orga
- to have a good selection of talks, we need some organizers who select a subset
  of whatever is submitted in the cfp.
- an experiment could be NOT to select talks, but just offer them all.

  space is not limited in cyberspace, but the time of the audience is.

info / emergency room
- one room where people can join in if they have general questions.
- help beginners / newscomers or if there are technical or social issues.

news room
- a news / blog like room for before / while / after the event

profiles
- personal
- project
- assembly

sprints / hackathons?
- have rooms for projects
- introduce people to a codebase / to a project's tools
- code together


Software / Tech we could use
----------------------------

Idea: not trying to reinvent the wheel, but reusing good existing free and open
soft- and hardware and just wrapping / integrating them as needed.

Django / PostgreSQL (all backend / database stuff, django admin, forms, search)

CSS / JS (browser based UI, good UX)

(parser for) markdown / reST markup for formatted content

BigBlueButton (teaching kind of stuff)

Mumble (telephony)

[Jitsi](https://jitsi.org/jitsi-meet/) (video conference)

WebRTC (if BBB is not enough, directly use this?)


