--------------------------------------------------------------------------
--------------------------------------------------------------------------
----------------------2017-3-29-note-by-cherry.zhang-----------------------------
--------------------------------------------------------------------------
--------------------------------------------------------------------------


��Ŀ�ܿ���ģ�飺

	��UCONabc���ݿ������ͷ��ʿ���ģ�ʹ���ݿ�)��
	��SFilter�ļ����������������ļ�����·�����ļ�����ִ�У�����д������Ȩ�޲���)��
	��NDIS��������������IP,Protocol,Port,URL,MAC�ȶ����ݽ��й���)��
	��WFP���������������û����̺źͽ��������������ݽ��й���)��
	��SSDT�û����̱���������������ǰ�ṩ��App���������Թ̶����̽���Ȩ�ޱ���)��
	������RW���ݿ�Ӧ�ó���APP�����ղ�ͬ�û���Ҫ��ĳ�ļ�,��ַ,IP,�˿ڸ���һ��Ȩ�޲�д�����ݿ�).

��װ˵����

  �������в���ƽ̨��windows 7 x86

  ����ƽ̨��windows 8.1 x64����wdk8.1+VS2013�� & windows 7 x64

  �������ߣ�QtCreator + WDK + VS2013 + VritualBox

  1.ʹ��mysql,�������ݿ⣬��Ϊucon,Ȼ�����(/uconsql/ucon.sql),����ʹ��Ŀ¼�µ�ucon�ļ����С�

  2.��Cp�ļ��У��Ȱ�װCredentialProvider,�ٰ�װCredentialProviderFilter(ע���ֱ�libmysql.dll��MCredentialProvider.dll��MCredentialProviderFilter.dll����c:/windows/system32Ŀ¼�·ֱ�˫��Register.reg��RegisterF.reg���а�װ)

  3.˫��LoadDriver.exe,����������װ(ע��NDIS������Ҫ������װ��������͹�������->��������������->��̫��->�Ҽ�->��װ->����->Ѱ��NDIS��������Ŀ¼�����а�װ)

  4.����SkyEye����,��һ��������Ҫע����Ϣ��dbname�����ݿ��������롱ucon������ɺ�����;

  ע��1.��װǰ�ر�ɱ��������  
      2.����ƾ����ʱ���������ȷ�������ȷ�˻�������ȷ��½���˴���bug������Լ��Ρ�
      3.NDIS������/NdisĿ¼��
      4.��������èͷӥ���棬�����Introduction��ǵõ���Ի���ť�ر�,�˴���bug������������������������
      5.��Ϊ������������ģ��Ľ���壬�ļ�ϵͳ����������ϵͳ�������ཻ��ͨ��pipe������Ϣ�������bug�����Ǹ��Ե������ж����������⡣

--------------------------------------------------------------------------

������sfilter project ��R0�ļ�ϵͳ����+R3Ӧ�ã����ֵĲ��ܱ������������ϵ��

	�����ߣ�steven.du����2544661922��QQ��

����������ѹ���ļ����ֵ���������ϵ��

	�����ߣ�cherry.zhang����591748932��QQ��