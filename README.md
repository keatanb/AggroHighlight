# **AggroHighlight**

re-adds the stripped aggro highlights functionality to the default raid frames as per the retail api code in https://github.com/tomrus88/BlizzardInterfaceCode/blob/master/Interface/FrameXML/CompactUnitFrame.lua

## Commands ##
    /ah --displays the color coding for different highlight threat situations

## Resources ##
    event: UNIT_THREAT_SITUATION_UPDATE
    method: _G.UnitThreatSituation
    

https://wowwiki-archive.fandom.com/wiki/API_GetThreatStatusColor

https://wowwiki-archive.fandom.com/wiki/API_UnitThreatSituation
