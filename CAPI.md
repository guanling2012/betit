betit
=====
�汾��0.1  
���ߣ�[���ķ�](mailto:809104518@qq.com)

���ĵ���������BetIt�Ŀͻ��˽ӿ�
******************************
����
----
* ���нӿ�
	*	[���Ѷ�̬�б�ӿ�](#���Ѷ�̬�б�ӿ�)
	*	[ȫ������б�ӿ�](#ȫվ��̬�б�ӿ�)
	*	[֪ͨ�б�ӿ�](#֪ͨ�б�ӿ�)
	*	[˽���б�ӿ�](#˽���б�ӿ�)
	*	[˽������]
	*	[�������а�ӿ�]
	*	[���Ŵ�����а�ӿ�]
	*	[�ҵĸ�����Ϣ]
	*	[�������]
	*	[�����б�]
	*	[�������]
	*	[��������]
	*	[�Ƽ�����б�]

* ���нӿ�
	*	[ע��]
	*	[��¼]
	*	[�������]
	*	[������]
	*	[׫д����]
	*	[����˽��]
	*	[����ͷ��]
	*	[�����ǳ�]
	*	[��д����]

�ӿ�˵��
--------

<h2>���Ѷ�̬�б�ӿ�</h2>
/capi/space.php?do=feed&uid=1&start=0&perpage=10&view=we
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- start
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ֵΪwe������Ѷ�̬�б�
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

<h2>ȫվ��̬�б�ӿ�</h2>
/capi/space.php?do=feed&uid=1&start=0&perpage=10&view=all
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- start
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ֵΪall����ȫվ��̬�б�
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

<h2>֪ͨ�б�ӿ�</h2>
/capi/space.php?do=notice&start=0&prepage=2&uid=1&type=quizinvalid
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- start
	* ÿҳ��ʾ����  -- perpage
	* ֪ͨ���� -- type
		* quiz -- ���
		* quizcomment -- �������
		* quizinvite -- �������
		* clickquiz -- ��ı�̬
		* quizwin -- ���Ӯ
		* quizlost -- �����
		* quizinvalid -- �����ʧ
		* credit -- ���
		* �� -- ����ȫ��֪ͨ
#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[notices]��֪ͨ�б� ��Ŀ�ֶ�����
			* id -- ֪ͨid
			* uid -- ����֪ͨ���û�
			* type -- ֪ͨ���ͣ�ȡֵ��������������
			* authorid -- ����֪ͨ���û�
			* authorid -- ����֪ͨ���û�
			* note -- ֪ͨ������
			* isfriend -- ���պͷ��ͷ��Ƿ����
			* dateline -- ʱ��
		* data[count], �����б���Ŀ��, ���ñ���
#### ����
	{"code":0,"data":{"notice":[{"id":"124","uid":"5","type":"quizwin","new":"0","authorid":"5","author":"summit","note":"��ϲ���� 
	<a href=\"space.php?uid=5&do=quiz&id=53\" target=\"_blank\">��234444444444444444��<\/a>�����ʹ���е�ʤ����ý��20��","dateline":"1344236803","isfriend":1,
	"style":""},{"id":"122","uid":"5","type":"quizlost","new":"0","authorid":"5","author":"summit","note":"�ܲ������� <a href=\"space.php?uid=5&do=quiz&id=52\" 
	target=\"_blank\">�������Ż�ȯ��<\/a>�����ʹ����û�л�ʤ�����˴��20�������Ŭ��o~�´εý��ľ����㣡","dateline":"1344236757","isfriend":1,"style":""},
	{"id":"120","uid":"5","type":"quizwin","new":"0","authorid":"5","author":"summit","note":"��ϲ���� <a href=\"space.php?uid=5&do=quiz&id=51\" target=\"_blank\">
	��34��<\/a>�����ʹ���е�ʤ����ý��20��","dateline":"1344236043","isfriend":1,"style":""},{"id":"118","uid":"5","type":"quizwin","new":"0","authorid":"5",
	"author":"summit","note":"��ϲ���� <a href=\"space.php?uid=5&do=quiz&id=50\" target=\"_blank\">��123��<\/a>�����ʹ���е�ʤ����ý��20��","dateline":"1344235975",
	"isfriend":1,"style":""},{"id":"116","uid":"5","type":"quizwin","new":"0","authorid":"5","author":"summit",
	"note":"��ϲ���� <a href=\"space.php?uid=5&do=quiz&id=49\" target=\"_blank\">�������Ż�ȯ��<\/a>�����ʹ���е�ʤ����ý��40��","dateline":"1344235733","isfriend":1,
	"style":""}],"count":5},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>˽���б�ӿ�</h2>
capi/space.php?do=pm&start=0&prepage=2&uid=1&filter=newpm
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- start
	* ÿҳ��ʾ����  -- perpage
	* ˽������ -- filter
		* newpm -- δ��˽��
		* privatepm -- ˽����Ϣ
		* systempm -- ϵͳ��Ϣ
		* announcepm -- ������Ϣ
		* �� -- ˽����Ϣ
#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[pms]��˽���б� ��Ŀ�ֶ�����
			* pmid -- ˽��id
			* msgfrom -- ��Ϣ������
			* msgfromid -- ��Ϣ������id
			* msgtoid -- ��Ϣ������id
			* authorid -- ����֪ͨ���û�
			* new -- �Ƿ�δ��
			* subject -- ˽�ű���
			* message -- ˽������
			* delstatus -- ɾ��״̬
			* fromappid -- Ӧ�ó���ID�����Ժ���
			* dateline -- ʱ��
			* daterange -- ��Ϣ�����������1����1���ڣ�2���������ڣ�3����3����
		* data[count], �����б���Ŀ��, ���ñ���
#### ����
	{"code":0,"data":{"pms":[{"pmid":"7","msgfrom":"admin","msgfromid":"1","msgtoid":"5","new":"1","subject":"���summit","dateline":"08-07 07:33","message":"���summit",
	"delstatus":"0","related":"0","fromappid":"1","daterange":1,"touid":"1"}],"count":1},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}