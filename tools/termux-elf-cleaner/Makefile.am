# Copyright (C) 2022 Termux

# This file is part of termux-elf-cleaner.

# termux-elf-cleaner is free software: you can redistribute it and/or
# modify it under the terms of the GNU General Public License as
# published by the Free Software Foundation, either version 3 of the
# License, or (at your option) any later version.

# termux-elf-cleaner is distributed in the hope that it will be
# useful, but WITHOUT ANY WARRANTY; without even the implied warranty
# of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# General Public License for more details.

# You should have received a copy of the GNU General Public License
# along with termux-elf-cleaner.  If not, see
# <https://www.gnu.org/licenses/>.

SUBDIRS = tests
AM_CXXFLAGS = -std=c++11 -Wall -Wextra -pedantic

bin_PROGRAMS = termux-elf-cleaner

termux_elf_cleaner_SOURCES = elf-cleaner.cpp arghandling.c
