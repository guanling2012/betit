betit
=====
�汾��0.1  
���ߣ�[���ķ�](mailto:809104518@qq.com)

���ĵ���������BetIt�Ŀͻ��˽ӿ�
******************************
����
----
*���нӿ�
	* ���Ѷ�̬�б�ӿ�
	* ȫ������б�ӿ�
	* ֪ͨ�б�ӿ�
	* ˽���б�ӿ�
	* ˽������
	* �������а�ӿ�
	* ���Ŵ�����а�ӿ�
	* �ҵĸ�����Ϣ
	* �������
	* �����б�
	* �������
	* ��������
	* �Ƽ�����б�

*���нӿ�
	* ע��
	* ��¼
	* �������
	* ������
	* ׫д����
	* ����˽��
	* ����ͷ��
	* �����ǳ�
	* ��д����

�ӿ�˵��
--------
<h2 id="friendfeed">ȫվ��̬�б�ӿ�</h2>
/capi/space.php?do=feed&uid=1&start=0&feedmaxnum=10
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- start
	* ÿҳ��ʾ����  -- feedmaxnum
#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[feeds]��feed�б� ��Ŀ�ֶ�����
			* feedid -- feed��idֵ
			* appid -- ��iconΪquizʱ���������
			* title_template -- feed�ı���
			* body_template -- feed������
			* dateline -- feed��ʱ��
			* uid -- ����feed���û�id
			* username -- ����feed�û�
			* image_1_link -- ���AͼƬ
			* image_2_link -- ���BͼƬ
			* idtype -- feed����
				* quizid -- ���
				* doid -- ����
				* picid -- ͼƬ
		* data[count], �����б���Ŀ��, ���ñ���
#### ����
{"code":0,"data":{"feeds":{"38527753d7ee50e50c95d6427110b925":{"feedid":"83","appid":"1","icon":"quiz","uid":"5","username":"summit","dateline":"08-06 07:11",
"friend":"0","hash_template":"d054367a46e659022b40f4334dec2c56","hash_data":"38527753d7ee50e50c95d6427110b925",
"title_template":"summit �����˴�� <a target=\"_blank\"   href=\"space.php?uid=5&do=quiz&id=54\"  target=\"_blank\">�����Ż�ȯ<\/a>�Ĵ𰸣�����3",
"title_data":{"url":"space.php?uid=5&do=quiz&id=54","subject":"�����Ż�ȯ","key":"3"},"body_template":"<br>��������1��,�ܲ��ұ���û���˻�ʤ�����Ҫ����Ӵ��",
"body_data":{"attend":"1"},"body_general":"","image_1":"","image_1_link":"","image_2":"","image_2_link":"","image_3":"","image_3_link":"","image_4":"",
"image_4_link":"","target_ids":"","id":"0","idtype":"","hot":"0","magic_class":"","icon_image":"image\/icon\/quiz.gif","target":" target=\"_blank\"",
"style":" onclick=\"readfeed(this, 83);\"","thisapp":1},"c6a4a0d241035ff650c7d2f841f387c8":{"feedid":"82","appid":"1","icon":"quiz","uid":"5","username":"summit",
"dateline":"08-06 07:10","friend":"0","hash_template":"d6269a47b34e39569585a1d028651f60","hash_data":"c6a4a0d241035ff650c7d2f841f387c8",
"title_template":"summit �������´��","title_data":[],"body_template":"<b><a target=\"_blank\"   href=\"space.php?uid=5&do=quiz&id=54\" >�����Ż�ȯ<\/a><\/b><br>
<br>12:2��Ͷע<br>3:1��Ͷע<br\/>���أ�60���","body_data":{"subject":"<a href=\"space.php?uid=5&do=quiz&id=54\">�����Ż�ȯ<\/a>",
"option":"<br>12:2��Ͷע<br>3:1��Ͷע","totalcost":"<br\/>���أ�60���"},"body_general":"","image_1":"","image_1_link":"","image_2":"","image_2_link":"",
"image_3":"","image_3_link":"","image_4":"","image_4_link":"","target_ids":"","id":"54","idtype":"quizid","hot":"0","magic_class":"","icon_image":"image\/icon\/quiz.gif","target":" target=\"_blank\"","style":"","thisapp":1}},"count":2},
"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}