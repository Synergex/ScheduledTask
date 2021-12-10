
Title:          ScheduledTask

Description:    A Traditional Synergy class implements a simple API to allow
                Traditional Synergy applications to be run as Windows Scheduled
                tasks.

Platforms:      Windows, Traditional Synergy

Synergy:        V10.1.1 or higher (may work with earlier versions)
  
Revision        2

Date:           16th October 2014

Author:         Steve Ives, Synergex Professional Services Group
                http://www.synergex.com

Notes for use:  To be able to run the code in this example you must set the
                logical name EXE: to point to the folder where you extracted
                the sample code. You can do this either in the real system
                level environment, or in the default symergy.ini file that
                is used by the default system environment (i.e. the one
                pointed to by the system wide SFWINIPATH setting). For
                example, you could add this code to your synergy .ini

                    [ScheduledTask]
                    EXE=C:\examples\ScheduledTask

                In its default configuration the code in this sample app
                schedules a task to run every minute, under the context
                of the SYSTEM account. Doing so requires administrator
                rights on the system. If you find that you are seeing
                "Failed to start task!" errors then make sure you are
                logged in to an administrative account, and make sure
                you start Workbench "As Administrator".

*****************************************************************************

 Copyright (c) 2014, Synergex International, Inc.
 All rights reserved.

 Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.

 * Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

 THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
 AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
 IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
 ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
 LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
 CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
 SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
 INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
 CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
 ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
 POSSIBILITY OF SUCH DAMAGE.

*****************************************************************************

