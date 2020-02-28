# vsanownerabdicate
abdicate ownership of vsan objects


get the <vsan object uuid>

cmmds-tool find -t DOM_OBJECT -f json -u <vsan object uuid>


vsish -e set /vmkModules/vsan/dom/ownerAbdicate <returned from cmmds-tools>
