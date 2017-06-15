from rsf.proj import *
Flow('vel',None,'''
      math n1=600 n2=600 d1=1 d2=1 type=abs output=2000
      label1=Distance label2=Distance unit1=m unit2=m unit=m/s
      ''')

Result('vel','grey scalebar=y')

Flow('shots','vel',
	'''
  modeling2d  nt=600 dt=0.001 ns=1 ng=60	
	sxbeg=200 szbeg=30 jsx=1 jsz=0 
	gxbeg=0 gzbeg=3 jgx=10 jgz=0 	
  cadgather=n fm=10
	''')


#Result('shots',
#	'''
#       byte allpos=n gainpanel=all |
#       grey3 flat=n frame1=300 frame2=100 frame3=5 
#       label1=Time unit1=s 
#       label2="Receiver no." label3="Shot no."
#       title="Shot records" point1=0.8 point2=0.8
#	''')
Result('shots','grey color=g title=shot scalebar=y')
Plot('shots','grey title=Shots',view=1)


End()
