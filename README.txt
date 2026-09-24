WARIO BLAST - LEVEL SELECT
Version 1.0
Release date: September 24, 2026
Platform: Nintendo Game Boy

OVERVIEW
========

Wario Blast - Level Select is a quality-of-life hack for Wario Blast
Featuring Bomberman! that adds a full LEVEL SELECT option to the title screen.

The original START and PASSWORD options remain intact. LEVEL SELECT lets you
choose any of the game's 32 normal stages, choose a starting Special Item
loadout, and then select Wario or Bomberman through the original Player Select
screen.

The hack is designed to make Wario Blast much easier to pick up and play while
preserving the original game whenever START or PASSWORD is used.

TITLE MENU
==========

  START
  LEVEL SELECT
  PASSWORD

START launches the original game normally.

PASSWORD retains the original four-digit password system and stock progression
behavior.

LEVEL SELECT opens the custom game setup.

LEVEL SELECT
============

Round: 1-8, plus EXTRA
Stage: 1 / 2 / 3 / BOSS
Power: NORMAL / NONE / KICKS / DASHIN / TROUNCER / LINER / ALL

After choosing settings, select START to continue to the original Player Select
screen.

ROUND EXTRA launches the original hidden THE BATTLE mode.

POWER SETTINGS
==============

NORMAL
  Uses the Special Items normally available at the selected stage.

NONE
  No permanent Special Items.

KICKS
  Kicks.

DASHIN
  Kicks + Dashin.

TROUNCER
  Kicks + Dashin + The Trouncer.

LINER
  Kicks + Dashin + The Trouncer + Liner.

ALL
  All five permanent Special Items, including Moto.

Custom POWER choices act as a starting floor rather than a permanent cap.
If normal progression later awards a Special Item beyond the chosen tier,
normal progression takes over.

POWER affects permanent Special Items only. Stage-specific rules remain
unchanged. Round 8, for example, still uses its normal maximum Extra Bomb and
Explosion Expander setup.

CONTROLS
========

Level Select:

  Up / Down      Move between menu rows
  Left / Right   Change Round, Stage, or Power
  A / Start      Begin when START is selected
  B              Return to the title screen

PASSWORD BEHAVIOR
=================

The original password system remains stock-compatible.

Passwords intentionally restore the game's normal stock state for the selected
stage rather than a custom POWER setting previously chosen through LEVEL SELECT.
Game Over passwords remain compatible with the original game.

PATCHING
========

Two patch formats are included:

  Wario Blast - Level Select.bps
  Wario Blast - Level Select.ips

BPS is recommended because it validates the source ROM.
IPS is included for compatibility with older patching utilities.

Apply ONE patch to a clean, unmodified copy of:

  Wario Blast Featuring Bomberman! (USA, Europe) (SGB Enhanced)

Do not apply both patches or patch an already modified ROM.

SOURCE ROM INFORMATION
======================

Name:    Wario Blast Featuring Bomberman! (USA, Europe) (SGB Enhanced)
Size:    262144 bytes
CRC32:   927B57A1
MD5:     14FE7234EE4BCB14ADF20C743F084A35
SHA-1:   279FB0223E362DB553B739B1B8F9C18B81D92413
SHA-256: 1AF2D4B29552FB2CF141955E1D77F8DD99E856B1F04FBFF5240D5A1C3C2C41BF

PATCHED ROM INFORMATION
=======================

Size:    262144 bytes
CRC32:   698126E3
MD5:     CEC1CCDB08544D523DCF3AEFAF8D7CEC
SHA-1:   7F64DCBCE4C39EE0866120BC2E6CE13F6071FF3D
SHA-256: 6677A57DEA30284AD4AAE7A91E84BB798263BCFE78FFAD50BE6C3DA24EA7A3F9

TESTING
=======

The final build was extensively tested with the SameBoy 1.0.3 emulation core,
including all 32 normal stages with both Wario and Bomberman, representative
POWER tiers, password behavior, normal START behavior, THE BATTLE, menu stress
testing, and stage-to-stage Special Item progression.

The final build was also tested on an original Game Boy DMG.

Super Game Boy functionality was tested in ares and behaved as expected.

CREDITS
=======

Hack / release: wavedout

Wario Blast Featuring Bomberman! was developed by Hudson Soft and published
by Nintendo.

This patch contains no original game ROM.

CHANGELOG
=========

v1.0 - September 24, 2026
- Added LEVEL SELECT to the title menu.
- Added access to all 32 normal stages.
- Added NORMAL / NONE / KICKS / DASHIN / TROUNCER / LINER / ALL starting
  Special Item tiers.
- Added direct access to THE BATTLE through ROUND EXTRA.
- Preserved original START and PASSWORD modes.
- Preserved stock password compatibility and Game Over passwords.
- Added correct Wario and Bomberman sprite handling for unusual underpowered
  late-round starts.
- Preserved Super Game Boy functionality.
