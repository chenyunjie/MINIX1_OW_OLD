MINIX 1.0 (OpenWATCOM + NASM + Bochs)

��飺
  Minix1.0��һ��16λ��΢�ں˲���ϵͳ��ԭ��������ʹ��PCIX����ϵͳ������
minix����������minix�ϼ���������Ҳ����dos��ʹ��C86��������MASM4.0���
������minix1.0��Ŀ�������������������Ѿ���ʱ��ѧϰ��ʵ������˲�С��
�ϰ���Ϊ�˱��˶�minix1.0������Ӧ���޸ģ���ʹ�����ִ�linux��windows��
ʹ��openwatcom��������nasm���������ϵͳ������ʹ��bochsģ�������к�
����ϵͳ���ڴ˰��޸ĺ��Դ�����ϴ�github��Ϊ�������ṩѧϰ�ı�������
�����ʿ���ϵ��e-mail:mumu3w@outlook.com��

1����װNASM
  CentOS7��
  yum install nasm
  Ubuntu:
  sudo apt install nasm

2����װopenwatcom
  https://github.com/open-watcom/travis-ci-ow-builds/archive/master.zip
  Rename to watcom
  mv ./watcom /opt/watcom
  
  export WATCOM=/opt/watcom
  export PATH=$WATCOM/binl64:$PATH (32:export PATH=$WATCOM/binl:$PATH)
  
3������
  cd MINIX1
  ./build.sh
  
4������
  cd MINIX1
  ./clean.sh

![image](https://github.com/mumu3w/MINIX1/blob/master/tools/2.PNG)

![image](https://github.com/mumu3w/MINIX1/blob/master/tools/1.PNG)
