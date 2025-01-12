# ------------------------------------------------------------------------------
# Quick Document
# ----------
# - basic config variable
#
# SetFontSize: [size:18-45]
#
# PlayEffect: [beam_color:Blue|Brown|Cyan|Green|Grey|Orange|Pink|White|Yellow]
#
# MinimapIcon: [size:0-2] [color] [logo:Circle|Diamond|Hexagon|Square|Star|Triangle|Cross|Moon|Raindrop|Kite|Pentagon|UpsideDownHouse]
#
# PlayAlertSound: [sound:1-16] [volume:0-300]
#
#
# ------------------------------------------------------------------------------


# ------------------------------------------------------------------------------
# Tier S: 500++
  SetFontSize 45
  SetTextColor 255 0 0 # red
  SetBorderColor 255 0 0 # red
  SetBackgroundColor 255 255 255 # white
  PlayEffect Red
  MinimapIcon 0 Red Star
  CustomAlertSound "sound/hey.mp3" 300

# ------------------------------------------------------------------------------
# Tier A+ : 100-500
  SetFontSize 45
  SetTextColor 255 0 0 200 # red
  SetBorderColor 255 0 0 200 # red
  SetBackgroundColor 255 255 255 200 # White
  PlayEffect Red
  MinimapIcon 0 Red Star
  CustomAlertSound "sound/hey.mp3" 300

# ------------------------------------------------------------------------------
# Tier A : 50-100
  SetFontSize 45
  SetTextColor 255 255 255 # white
  SetBorderColor 255 255 255 # white
  SetBackgroundColor 255 160 122 # light salmon
  PlayEffect Red
  MinimapIcon 0 Red Circle
  CustomAlertSound "sound/hey.mp3" 300

# ------------------------------------------------------------------------------
# Tier B : 10-50
  SetFontSize 40
  SetTextColor 0 0 0 # black
  SetBorderColor 0 0 0 # black
  SetBackgroundColor 255 160 122 # light salmon
  PlayEffect Yellow
  MinimapIcon 1 Yellow Circle
  CustomAlertSound "sound/cash_machine.mp3" 300
  
# ------------------------------------------------------------------------------
# Tier C : 1-10
  SetFontSize 35
  SetTextColor 0 0 0 # black
  SetBorderColor 0 0 0 # black
  SetBackgroundColor 218 165 32 # golden rod
  PlayEffect White
  MinimapIcon 2 White Circle
  CustomAlertSound "sound/cash_machine.mp3" 100


# ------------------------------------------------------------------------------
# Tier D : < 1
  SetTextColor 0 0 0 # black
  SetBorderColor 0 0 0 # black
  SetBackgroundColor 173 255 47 # green yellow

# ------------------------------------------------------------------------------
# Quest Item
  SetTextColor 216 191 216 # thistle
  SetBorderColor 216 191 216 # thistle
  SetBackgroundColor 75 0 130 # indigo (purple)