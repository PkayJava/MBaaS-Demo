# MBaaS-Demo

:/>gradle mbaasLayout -PclassName="HelloLayout" -Ptitle="Hello Layout" -Pdescription="Hello Layout"

:/>gradle mbaasPage -PclassName="HelloPage" -Playout="Hello Layout" -PmountPath="/hello" -Ptitle="Hello Page" -Pcode="HELLO" -Pdescription="Hello Page"

:/>gradle mbaasRest -PclassName="HelloRest" -Pname="Hello Rest" -PmountPath="/hello" -Pmethod="GET" -Pdescription="Hello Rest"

:/>gradle mbaasSync

http://mbaas.angkorteam.com/api/hello
