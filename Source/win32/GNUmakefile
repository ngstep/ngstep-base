#
#  src makefile for the GNUstep Base Library
#
#  Copyright (C) 1997 Free Software Foundation, Inc.
#
#  Written by:	Scott Christley <scottc@net-community.com>
#
#  This file is part of the GNUstep Base Library.
#
#  This library is free software; you can redistribute it and/or
#  modify it under the terms of the GNU Lesser General Public
#  License as published by the Free Software Foundation; either
#  version 2 of the License, or (at your option) any later version.
#
#  This library is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.	 See the GNU
#  Library General Public License for more details.
#
#  You should have received a copy of the GNU Lesser General Public
#  License along with this library; if not, write to the Free
#  Software Foundation, Inc., 31 Milk Street #960789 Boston, MA 02196 USA.#

PACKAGE_NAME = gnustep-base
GNUSTEP_LOCAL_ADDITIONAL_MAKEFILES=../../base.make

include $(GNUSTEP_MAKEFILES)/common.make
include ../../config.mak

SUBPROJECT_NAME = win32

win32_OBJC_FILES =\
	GSFileHandle.m \
	GSRunLoopCtxt.m \
	NSMessagePort.m \
	NSMessagePortNameServer.m \
	NSStream.m \
	NSUserDefaults.m \
	NSString+Win32Additions.m\

-include Makefile.preamble

include $(GNUSTEP_MAKEFILES)/subproject.make

-include Makefile.postamble
