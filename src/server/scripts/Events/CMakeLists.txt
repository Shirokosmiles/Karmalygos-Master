# Copyright (C) 2011-2016 Project SkyFire <http://www.projectskyfire.org/
# Copyright (C) 2008-2016 TrinityCore <http://www.trinitycore.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
  Events/brewfest.cpp
  Events/childrens_week.cpp
  Events/hallows_end.cpp
  Events/midsummer_fire_festival.cpp
  Events/pilgrims_bounty.cpp
  Events/winter_veil.cpp
  Events/event_afd_royale.cpp
)

message("  -> Prepared: Events")
