# Copyright 2015, Stephen Fryatt (info@stevefryatt.org.uk)
#
# This file is part of Wimp Programming In C:
#
#   http://www.stevefryatt.org.uk/risc-os/wimp-prog
#
# Licensed under the EUPL, Version 1.2 only (the "Licence");
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

COMPONENT = main

OBJS = main ibar

CINCLUDES = -IC:,OSLib:,SFLib:
LIBS = SFLib:o.SFLib OSLib:o.OSLib32

include CApp

# Dynamic dependencies:
o.main:	c.main
o.main:	OSLib:oslib.h.wimp
o.main:	OSLib:oslib.h.types
o.main:	OSLib:oslib.h.os
o.main:	OSLib:oslib.h.oscore32
o.main:	OSLib:oslib.h.osf32
o.main:	OSLib:oslib.h.osspriteop
o.main:	OSLib:oslib.h.font
o.main:	OSLib:oslib.h.wimp32
o.main:	SFLib:sflib.h.event
o.main:	OSLib:oslib.h.types
o.main:	OSLib:oslib.h.wimp
o.main:	h.ibar
o.main:	OSLib:oslib.h.wimp
o.ibar:	c.ibar
o.ibar:	OSLib:oslib.h.wimp
o.ibar:	OSLib:oslib.h.types
o.ibar:	OSLib:oslib.h.os
o.ibar:	OSLib:oslib.h.oscore32
o.ibar:	OSLib:oslib.h.osf32
o.ibar:	OSLib:oslib.h.osspriteop
o.ibar:	OSLib:oslib.h.font
o.ibar:	OSLib:oslib.h.wimp32
o.ibar:	h.ibar
o.ibar:	OSLib:oslib.h.wimp
