# Copyright 2015-2020, Stephen Fryatt (info@stevefryatt.org.uk)
#
# This file is part of Wimp Programming In C:
#
#   http://www.stevefryatt.org.uk/software/
#
# Licensed under the EUPL, Version 1.1 only (the "Licence");
# You may not use this work except in compliance with the
# Licence.
#
# You may obtain a copy of the Licence at:
#
#   http://joinup.ec.europa.eu/software/page/eupl
#
# Unless required by applicable law or agreed to in
# writing, software distributed under the Licence is
# distributed on an "AS IS" basis, WITHOUT WARRANTIES
# OR CONDITIONS OF ANY KIND, either express or implied.
#
# See the Licence for the specific language governing
# permissions and limitations under the Licence.

# Makefile for Example App

COMPONENT = !ExamplApp.!RunImage

OBJS = calc main menu ibar win

CINCLUDES = -IC:,OSLib:,SFLib:
LIBS = SFLib:o.SFLib OSLib:o.OSLib32

include CApp

C_NO_FNAMES =

# Dynamic dependencies:
o.calc:	c.calc
o.calc:	SFLib:sflib.h.string
o.calc:	OSLib:oslib.h.types
o.calc:	h.calc
o.main:	c.main
o.main:	OSLib:oslib.h.osspriteop
o.main:	OSLib:oslib.h.types
o.main:	OSLib:oslib.h.os
o.main:	OSLib:oslib.h.oscore32
o.main:	OSLib:oslib.h.osf32
o.main:	OSLib:oslib.h.wimp
o.main:	OSLib:oslib.h.font
o.main:	OSLib:oslib.h.wimp32
o.main:	SFLib:sflib.h.errors
o.main:	OSLib:oslib.h.messagetrans
o.main:	OSLib:oslib.h.wimp
o.main:	SFLib:sflib.h.event
o.main:	OSLib:oslib.h.types
o.main:	OSLib:oslib.h.wimp
o.main:	SFLib:sflib.h.resources
o.main:	OSLib:oslib.h.osspriteop
o.main:	SFLib:sflib.h.url
o.main:	h.main
o.main:	h.calc
o.main:	h.ibar
o.main:	h.win
o.main:	OSLib:oslib.h.osspriteop
o.menu:	c.menu
o.menu:	OSLib:oslib.h.wimp
o.menu:	OSLib:oslib.h.types
o.menu:	OSLib:oslib.h.os
o.menu:	OSLib:oslib.h.oscore32
o.menu:	OSLib:oslib.h.osf32
o.menu:	OSLib:oslib.h.osspriteop
o.menu:	OSLib:oslib.h.font
o.menu:	OSLib:oslib.h.wimp32
o.menu:	h.menu
o.menu:	OSLib:oslib.h.wimp
o.ibar:	c.ibar
o.ibar:	OSLib:oslib.h.wimp
o.ibar:	OSLib:oslib.h.types
o.ibar:	OSLib:oslib.h.os
o.ibar:	OSLib:oslib.h.oscore32
o.ibar:	OSLib:oslib.h.osf32
o.ibar:	OSLib:oslib.h.osspriteop
o.ibar:	OSLib:oslib.h.font
o.ibar:	OSLib:oslib.h.wimp32
o.ibar:	SFLib:sflib.h.errors
o.ibar:	OSLib:oslib.h.messagetrans
o.ibar:	OSLib:oslib.h.wimp
o.ibar:	SFLib:sflib.h.event
o.ibar:	OSLib:oslib.h.types
o.ibar:	OSLib:oslib.h.wimp
o.ibar:	SFLib:sflib.h.windows
o.ibar:	OSLib:oslib.h.wimp
o.ibar:	SFLib:sflib.h.url
o.ibar:	h.ibar
o.ibar:	h.main
o.ibar:	h.menu
o.ibar:	OSLib:oslib.h.wimp
o.ibar:	h.win
o.ibar:	OSLib:oslib.h.osspriteop
o.win:	c.win
o.win:	OSLib:oslib.h.osspriteop
o.win:	OSLib:oslib.h.types
o.win:	OSLib:oslib.h.os
o.win:	OSLib:oslib.h.oscore32
o.win:	OSLib:oslib.h.osf32
o.win:	OSLib:oslib.h.wimp
o.win:	OSLib:oslib.h.font
o.win:	OSLib:oslib.h.wimp32
o.win:	SFLib:sflib.h.debug
o.win:	SFLib:sflib.h.errors
o.win:	OSLib:oslib.h.messagetrans
o.win:	OSLib:oslib.h.wimp
o.win:	SFLib:sflib.h.event
o.win:	OSLib:oslib.h.types
o.win:	OSLib:oslib.h.wimp
o.win:	SFLib:sflib.h.icons
o.win:	OSLib:oslib.h.wimp
o.win:	SFLib:sflib.h.menus
o.win:	OSLib:oslib.h.wimp
o.win:	SFLib:sflib.h.string
o.win:	OSLib:oslib.h.types
o.win:	SFLib:sflib.h.windows
o.win:	OSLib:oslib.h.wimp
o.win:	h.win
o.win:	OSLib:oslib.h.osspriteop
o.win:	h.menu
o.win:	OSLib:oslib.h.wimp
o.win:	h.calc
