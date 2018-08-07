#!/usr/bin/env python 3
import sys
global portList

portList = []
portList.append(22)
portList.append(21)
portList.append(25)
portList.append(80)
portList.append(443)
portList.append(110)

portList.sort()
cnt = len(portList)

print(portList)




