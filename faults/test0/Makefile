#	*******************************************
#	*							make a fault								*
#	*					Author: Yanwen Wei							*
#	*					Email: wei_yanwen@163.com				*
#	*					Date: 2017/6/13 ---							*
#	*******************************************

# parameters

mag	=	0,1500,-1500
nsp	=	3
d1	=	10
d2	=	1
unit1	=	m
unit2	=	m
#unit	=	m/s
label1	=	Distance
label2	= Distance
n1	=	500
n2	=	400
o1	=	0
o2	=	0
k1	=	1,200,201
l1	=	500,400,401
k2	=	1,150,150
l2	=	400,250,200
p1	=	0,0,0
p2	=	0,0,2


#	sfspike
.PHONY:all

all:
	sfspike mag=${mag} nsp=${nsp} d1=${d1} d2=${d2} unit1=${unit1} unit2=${unit2} label=${label1} label2=${label2}\
		n1=${n1} n2=${n2} o1=${o1} o2=${o2} k1=${k1} k2=${k2} l1=${l1} l2=${l2} p1=${p1} p2=${p2} | sfgrey scalebar=y | sfpen

