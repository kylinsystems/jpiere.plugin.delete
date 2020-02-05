# KBS Plugin :JPIERE Delete Client and Initial Client

The fork from https://github.com/JPiere/jpiere.plugin.delete, and converted to be installed via **KBS ObjectData Tool** 

Refer to http://wiki.idempiere.org/en/Plugin:_Delete_Client_and_Initialize_Client

## How to install

1. Install **KBS ObjectData Tool** (refer to http://wiki.idempiere.org/en/Plugin:_ObjectDataTool)

2. Install the plugin via Apache Felix Web Console

## How to use

System Admin -> General Rules -> Printing -> Print Format ???

## Fixing

PackOut.xml : change wrong entitytype from <EntityType>U</EntityType> to <EntityType>JP</EntityType>

Run **UUID Generator** to generate value of ad_treenodemm.ad_treenodemm_uu for all 5 menus within this plugin, it is mandatory for plugin installation by **KBS ObjectData Tool**