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
	*	[˽������](#˽������)
	*	[�������а�ӿ�](#�������а�ӿ�)
	*	[���Ŵ�����а�ӿ�](#���Ŵ�����а�ӿ�)
	*	[�ҵĸ�����Ϣ](#�ҵĸ�����Ϣ)
	*	[�������](#�������)
	*	[�����б�](#�����б�)
	*	[�������](#�������)
	*	[��������](#��������)
	*	[�Ƽ�����б�](#�Ƽ�����б�)

* ���нӿ�
	*	[��ȡע����֤��](#��ȡע����֤��)
	*	[ע��](#ע��)
	*	[��¼](#��¼)
	*	[�ϴ�ͼƬ](#�ϴ�ͼƬ)
	*	[�������](#�������)
	*	[������](#������)
	*	[׫д����](#׫д����)
	*	[����˽��](#����˽��)
	*	[����ͷ��]
	*	[�����ǳ�](#�����ǳ�)
	*	[��д����](#��д����)

�ӿ�˵��
--------

<h2>���Ѷ�̬�б�ӿ�</h2>
/capi/space.php?do=feed&uid=1&page=0&perpage=10&view=we&m_auth=55dalDuJytwHteL6s5qlKwHLmhIhpGZ4fZUXHu0
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ֵΪwe������Ѷ�̬�б�
	* API��Կ -- m_auth, �ɵ�¼�󷵻�
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
/capi/space.php?do=feed&uid=1&page=0&perpage=10&view=all&m_auth=55dalDuJytwHteL6s5qlKwHLmhIhpGZ4fZUXHu0
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ֵΪall����ȫվ��̬�б�
	* API��Կ -- m_auth, �ɵ�¼�󷵻�
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
/capi/space.php?do=notice&page=0&prepage=2&uid=1&type=quizinvalid&m_auth=55dalDuJytwHteL6s5qlKwHLmhIhpGZ4fZUXHu0
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- page
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
	* API��Կ -- m_auth, �ɵ�¼�󷵻�
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
capi/space.php?do=pm&page=0&prepage=2&uid=1&filter=newpm&m_auth=55dalDuJytwHteL6s5qlKwHLmhIhpGZ4fZUXHu0
#### �������
	* ��ǰ�û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ˽������ -- filter
		* newpm -- δ��˽��
		* privatepm -- ˽����Ϣ
		* systempm -- ϵͳ��Ϣ
		* announcepm -- ������Ϣ
		* �� -- ˽����Ϣ
	* API��Կ -- m_auth, �ɵ�¼�󷵻�
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

<h2>˽������</h2>
capi/space.php?do=pm&subop=view&pmid=2&touid=12&daterange=10&m_auth=55dalDuJytwHteL6s5qlKwHLmhIhpGZ4fZUXHu0
#### �������
	* ��Ϣ�������û�id -- touid
	* ������Ϣ�����䣨����֮�ڵģ� -- daterange
	* ��Ϣid -- pmid
	* �������� -- subop, ����Ϊview
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

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
	{"code":0,"data":{"pms":[{"pmid":"3","msgfrom":"aifaxian","msgfromid":"1","msgtoid":"12","folder":"inbox","new":"1","subject":"��ð�","dateline":"03-09 18:04",
	"message":"��ð�","delstatus":"0","related":"1","fromappid":"1","daterange":5}],"count":1},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>�������а�ӿ�</h2>
capi/space.php?uid=5&do=friend&m_auth=54f8qnt8HxbRz8NWomy0e4k2gKvVvc6oil8qDY9upUERswmzj
#### �������
	* ��ǰ�û�id -- uid
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[friends]�������б� ��Ŀ�ֶ�����(������[��¼](#��¼)���صĿռ���Ϣ
			* groupid -- �����û��飨����
			* credit -- ���
			* experience -- ����
			* username -- �û���
			* name -- ʵ��
			* namestatus -- �Ƿ�ʵ��
			* videostatus -- �Ƿ���Ƶ��֤
			* friendnum -- ������
			* viewnum -- �������
			* notenum -- ֪ͨ��
			* addfriendnum -- ��ע��
			* doingnum -- ������
			* lastpost -- �����ύʱ��
			* lastlogin -- ���µ�¼ʱ��
			* attachsize -- �ռ��С
			* flag -- �Ƿ񱻽�
			* newpm -- �Ƿ�����֪ͨ
			* avatar -- ����ͷ��
			* quiznum -- �����Ĵ����
			* winnum -- Ӯ�Ĵ���
			* lostnum -- ��Ĵ���
			* voternum -- �μӴ�ĵĴ���
		* data[count], �����б���Ŀ��, ���ñ���

#### ����
	{"code":0,"data":{"friends":{"7":{"uid":"7","groupid":"11","credit":"1800","experience":"2000","username":"test2","name":"","namestatus":"0","videostatus":"0",
	"domain":"","friendnum":"1","viewnum":"4","notenum":"6","addfriendnum":"0","mtaginvitenum":"0","eventinvitenum":"0","myinvitenum":"0","pokenum":"0",
	"doingnum":"0","blognum":"0","albumnum":"0","threadnum":"0","pollnum":"0","eventnum":"0","sharenum":"0","dateline":"1343973929","updatetime":"1343974426",
	"lastsearch":"0","lastpost":"1343974426","lastlogin":"1343974880","lastsend":"0","attachsize":"0","addsize":"0","addfriend":"0","flag":"0","newpm":"0",
	"avatar":"0","regip":"127.0.0.1","ip":"127000000","mood":"0","quiznum":"1","winnum":"0","lostnum":"0","voternum":"1","resideprovince":"","residecity":"",
	"note":"","spacenote":"","sex":"0","gid":"0","num":"6","p":"","c":"","group":"����","isfriend":1}},"count":1},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>���Ŵ�����а�ӿ�</h2>
capi/space.php?uid=5&do=quiz&page=0&perpage=2&view=hot&m_auth=54f8qnt8HxbRz8NWomy0e4k2gKvVvc6oil8qDY9upUERswmzj17Dt8R%252B652pTEKjHTOgNjgJ80RzLSsp7vbN
#### �������
	* �û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ����Ϊhot
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[quizs]������б� ��Ŀ�ֶ�����
			* ���id : quizid
			* ������ĵ��û�id : uid
			* ������ĵ��û��� : username
			* ��ı���: subject
			* �������: viewnum
			* �ظ�������replynum
			* �ȶ�: hot
			* ʱ��: dateline
			* ����������: joincost
			* �������Ͷע����: portion
			* ��ֹʱ��: endtime
			* Ԥ�ƹ������ʱ��: resulttime
			* ���һ��ͶƱʱ��: lastvote
			* �����ĵ�����: voternum
			* ��id: keyoid
			* ��: keyoption
			* �����: totalcost
		* data[count], �����б���Ŀ��, ���ñ���
#### ����
	{"code":0,"data":{"quizs":[{"quizid":"48","topicid":"0","uid":"7","username":"test2","subject":"23123","classid":"0","viewnum":"2","replynum":"0","hot":"2",
	"dateline":"1343974426","pic":"","picflag":"0","noreply":"0","friend":"0","password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0","click_5":"0",
	"joincost":"100","portion":"3","endtime":"1344579220","resulttime":"1344582820","lastvote":"1343974888","voternum":"3","maxchoice":"0","sex":"0","keyoid":"0",
	"keyoption":"","totalcost":"400","hasremind":"0","hasexceed":"0","tag":"","message":"","postip":"127.0.0.1","related":"","relatedtime":"0","target_ids":"",
	"hotuser":"1,5","magiccolor":"0","magicpaper":"0","magiccall":"0","option":["1221","123123"],"invite":"","optioncount":["3","1"]},{"quizid":"49","topicid":"0",
	"uid":"5","username":"summit","subject":"�����Ż�ȯ","classid":"0","viewnum":"1","replynum":"0","hot":"1","dateline":"1344235585","pic":"","picflag":"0",
	"noreply":"0","friend":"0","password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0","click_5":"0","joincost":"20","portion":"3",
	"endtime":"1344235733","resulttime":"1344843977","lastvote":"1344235654","voternum":"2","maxchoice":"0","sex":"0","keyoid":"95","keyoption":"23",
	"totalcost":"120","hasremind":"0","hasexceed":"0","tag":"","message":"","postip":"127.0.0.1","related":"","relatedtime":"0","target_ids":"","hotuser":"1",
	"magiccolor":"0","magicpaper":"0","magiccall":"0","option":["23","2"],"invite":"","optioncount":["4","2"]}],"count":2},"msg":"���ݻ�ȡ�ɹ�",
	"action":"rest_success"}

<h2>�ҵĸ�����Ϣ</h2>
capi/cp.php?ac=profile&m_auth=65e8JkX8RscU2y2pYZEVdcZrja2YOr2QXuhbPBCHzLAw
#### �������
	* API��Կ -- m_auth, �ɵ�¼�󷵻�
#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ����������һ������
		* data[space], ��ǰ��¼�û�����Ϣ��������������
			* �û�id -- uid
			* �Ա� -- sex, ��ȡֵ0�� Ůȡֵ1
			* �û����� -- email
			* �ֻ� -- mobile
			* qq�ʺ� -- qq
			* msn�ʺ� -- msn
			* weibo�ʺ� -- weibo
			* ��˽���� -- privacy, ����������0����ȫվ�ɼ�
			* ��̬���� -- feed, ����������
			* ������ -- friend
			* ��̬������ -- feedfriend
			* ��� -- credit
			* ���� -- experience
			* �û��� -- username
			* ʵ�� -- name
			* �Ƿ�ʵ�� -- namestatus, 1��, 0��
			* ������ -- doingnum
			* ������ -- sharenum
			* �����Ծʱ�� -- dateline
			* �������ʱ�� -- updatetime
			* ���һ������ʱ�� -- lastsearch
			* ���һ�η���ʱ�� -- lastpost
			* ���һ�ε�¼ʱ�� -- lastlogin
			* ���һ�η�����Ϣʱ�� -- lastsend
			* �Ƿ���� -- flag
			* �Ƿ�����֪ͨ -- newpm
			* ͷ�� -- avatar
			* ��¼��ip -- ip
			* ������С -- attachsize
			* �����Ĵ���� -- quiznum
			* Ӯ�Ĵ��� -- winnum
			* ��Ĵ��� -- lostnum
			* �������� -- voternum
			* �����б�id -- friends

			
#### ����
	{"code":0,"data":{"space":{"uid":"5","sex":"0","email":"summit_mail@qq.com","newemail":"","emailcheck":"0","mobile":"","qq":"","msn":"","msnrobot":"",
	"msncstatus":"0","videopic":"","birthyear":"0","birthmonth":"0","birthday":"0","blood":"","note":"","spacenote":"","authstr":"","theme":"","nocss":"0","menunum":"0","css":"","privacy":{"view":{"index":"0","friend":"0","wall":"0",
	"feed":"0","doing":"0","quiz":"0","share":"0"},"feed":{"doing":1,"quiz":1,"joinquiz":1,"share":1,"post":1,"join":1,"friend":1,"comment":1,"credit":1,"spaceopen":1,"invite":1,
	"task":1,"profile":1,"click":1}},"friend":"7","feedfriend":"7","sendmail":"","magicstar":"0","magicexpire":"0","timeoffset":"","weibo":"","groupid":"11",
	"credit":"2007","experience":"2047","username":"summit","name":"","namestatus":"0","videostatus":"0","domain":"","friendnum":"1","viewnum":"5","notenum":"0",
	"addfriendnum":"0","doingnum":"0","sharenum":"0","dateline":"1343789930","updatetime":"1344237052","lastsearch":"0","lastpost":"1344324259","lastlogin":"1344395688",
	"lastsend":"0","attachsize":"0","addsize":"0","addfriend":"0","flag":"0","newpm":"0","avatar":"0","regip":"127.0.0.1","ip":"127000000","mood":"0",
	"quiznum":"8","winnum":"4","lostnum":"1","voternum":"7","self":1,"friends":["7"],"allnotenum":0}},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>�������</h2>
capi/space.php?do=quiz&id=54&uid=5&m_auth=af9cCEMpQlfFTifZltugadwhGAXL%2Ba%2BCor8voR9jZyBh60v4xFryq2ibMM1tNHXaHYweU%2B8hsBHobKzgHFJs

#### �������
	* ���id -- id
	* �����˴�ĵ��û�id -- uid
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ����������һ������
		* data[quiz], ������飬������������
			* ���id -- quizid
			* ��������û�id -- uid
			* �����û� -- hotuser
			* ����ʱ�� -- dateline
			* Ͷһע������ -- joincost
			* �û����Ͷע�� -- portion
			* ��ֹͶעʱ�� -- endtime
			* Ԥ�ƹ������ʱ�� -- resulttime
			* ���һ��Ͷעʱ�� -- lastvote
			* ��ǰ�ۼ�Ͷע -- voternum
			* ����� -- totalcost
			* �Ƿ��Ѿ����ѹ� -- hasremind
			* �Ƿ��Ѿ����� -- hasexceed
			* ��ѡ��id -- keyoid
			* �� -- keyoption
			* ѡ������ -- options�������������£�
				* ѡ��id -- oid
				* �������� -- quizid
				* �û�id -- uid
				* ѡ�� -- option, �ı�����
				* ��Ƭid -- picid
				* ��Ƭ·�� -- pic
				* Ͷע���� -- votenum
				* Ͷעռ��Ͷע�ٷֱ� -- percent

#### ����
	{"code":0,"data":{"quiz":{"quizid":"54","uid":"5","hotuser":"","option":"a:2:{i:0;s:2:\"12\";i:1;s:1:\"3\";}","invite":"","topicid":"0","username":"summit",
	"subject":"�����Ż�ȯ","classid":"0","viewnum":"0","replynum":"0","hot":"0","dateline":"1344237052","pic":"","picflag":"0","noreply":"0",
	"friend":"0","password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0","click_5":"0","joincost":"20","portion":"3","endtime":"1344237071",
	"resulttime":"1344845443","lastvote":"1344237066","voternum":"1","maxchoice":"0","sex":"0","keyoid":"106","keyoption":"3","totalcost":"60","hasremind":"0",
	"hasexceed":"0","options":[{"oid":"105","quizid":"54","uid":"5","option":"12","relatedtime":"1344237052","picid":"0","votenum":"2","percent":67,"width":107},
	{"oid":"106","quizid":"54","uid":"5","option":"3","relatedtime":"1344237052","picid":"0","votenum":"1","percent":33,"width":53}]}},

<h2>�����б�</h2>
capi/do.php?ac=ajax&op=getcomment&id=24&idtype=quizid&page=0&prepage=1&m_auth=af9cCEMpQlfFTifZltugadwhG

#### �������
	* �������� -- op, ����Ϊgetcomment
	* ��ѯ���۹�����id -- id, ��Ϊ��ģ���Ϊ���idֵ����Ϊ�ռ���Ϊ�û�idֵ����Ϊ������Ϊ����idֵ
	* ָʾid��������� -- idtype, quizid�����ģ�uid����ռ�, sid�������
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[comments],�����б�������������
			* ����id -- cid
			* ���۶����û�id -- uid
			* ���۹�����id -- id
			* �������� -- idtype
			* �������۵��û�id -- authorid
			* �������۵��û��� -- author
			* �����ʱ�� -- dateline
			* �����ip -- ip
			* ���۵����� -- message
		* data[count], �����б���Ŀ��, ���ñ���

#### ����
	{"code":0,"data":{"comments":[{"cid":"31","uid":"1","id":"24","idtype":"quizid","authorid":"1","author":"admin","ip":"127.0.0.1","dateline":"1344407149",
	"message":"234234"}],"count":1},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>�������</h2>
capi/space.php?uid=5&do=quiz&page=0&perpage=2&view=new&searchkey=����&m_auth=af9cCEMpQ
#### �������
	* �û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ����Ϊnew
	* ��ѯ���� -- searchkey
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[quizs]������б� ��Ŀ�ֶ�����
			* ���id : quizid
			* ������ĵ��û�id : uid
			* ������ĵ��û��� : username
			* ��ı���: subject
			* �������: viewnum
			* �ظ�������replynum
			* �ȶ�: hot
			* ʱ��: dateline
			* ����������: joincost
			* �������Ͷע����: portion
			* ��ֹʱ��: endtime
			* Ԥ�ƹ������ʱ��: resulttime
			* ���һ��ͶƱʱ��: lastvote
			* �����ĵ�����: voternum
			* ��id: keyoid
			* ��: keyoption
			* �����: totalcost
		* data[count], �����б���Ŀ��, ���ñ���
		* data[reward], ��ѯ�����۳��Ľ�Һ�����

#### ����
	{"code":0,"data":{"quizs":[{"quizid":"54","topicid":"0","uid":"5","username":"summit","subject":"�����Ż�ȯ",
	"classid":"0","viewnum":"1","replynum":"0","hot":"0","dateline":"1344237052","pic":"","picflag":"0",
	"noreply":"0","friend":"0","password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0",
	"click_5":"0","joincost":"20","portion":"3","endtime":"1344237071","resulttime":"1344845443",
	"lastvote":"1344237066","voternum":"1","maxchoice":"0","sex":"0","keyoid":"106","keyoption":"3",
	"totalcost":"60","hasremind":"0","hasexceed":"0","tag":"","message":"","postip":"127.0.0.1","related":"",
	"relatedtime":"0","target_ids":"","hotuser":"","magiccolor":"0","magicpaper":"0","magiccall":"0",
	"option":["12","3"],"invite":"","optioncount":["2","1"]},{"quizid":"52","topicid":"0","uid":"5",
	"username":"summit","subject":"�����Ż�ȯ","classid":"0","viewnum":"0","replynum":"0","hot":"0",
	"dateline":"1344236417","pic":"","picflag":"0","noreply":"0","friend":"0","password":"","click_1":"0",
	"click_2":"0","click_3":"0","click_4":"0","click_5":"0","joincost":"20","portion":"3","endtime":"1344236757",
	"resulttime":"1344844795","lastvote":"1344236423","voternum":"1","maxchoice":"0","sex":"0","keyoid":"102",
	"keyoption":"����","totalcost":"20","hasremind":"0","hasexceed":"0","tag":"","message":"",
	"postip":"127.0.0.1","related":"","relatedtime":"0","target_ids":"","hotuser":"","magiccolor":"0",
	"magicpaper":"0","magiccall":"0","option":["��","����"],"invite":"","optioncount":["1","0"]}],"count":2,
	"reward":{"credit":1,"experience":0}},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>��������</h2>
capi/cp.php?ac=friend&op=search&page=0&perpage=1&searchkey=admin&searchsubmit=true&searchmode=1&m_auth=af9cCEMpQ
#### �������
	* �û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- searchsubmit����Ϊtrue, searchmode����Ϊ1
	* ��ѯ���� -- searchkey
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[friend]������б� ��Ŀ�ֶ�����
			* �û�id -- uid
			* ��� -- credit
			* ���� -- experience
			* �û��� -- username
			* ʵ�� -- name
			* �Ƿ�ʵ�� -- namestatus, 1��, 0��
			* ������ -- doingnum
			* ������ -- sharenum
			* �����Ծʱ�� -- dateline
			* �������ʱ�� -- updatetime
			* ���һ������ʱ�� -- lastsearch
			* ���һ�η���ʱ�� -- lastpost
			* ���һ�ε�¼ʱ�� -- lastlogin
			* ���һ�η�����Ϣʱ�� -- lastsend
			* �Ƿ���� -- flag
			* �Ƿ�����֪ͨ -- newpm
			* ͷ�� -- avatar
			* ��¼��ip -- ip
			* ������С -- attachsize
			* �����Ĵ���� -- quiznum
			* Ӯ�Ĵ��� -- winnum
			* ��Ĵ��� -- lostnum
			* �������� -- voternum
			* �Ƿ����-- isfriend, 0��1��
		* data[count], �����б���Ŀ��, ���ñ���

#### ����
	{"code":0,"data":{"friends":{"1":{"uid":"1","groupid":"11","credit":"2042","experience":"2045",
	"username":"admin","name":"","namestatus":"0","videostatus":"0","domain":"","friendnum":"0","viewnum":"3",
	"notenum":"0","doingnum":"0","sharenum":"0","dateline":"1343725030","updatetime":"1343966557","lastsearch":"1344408548","lastpost":"1344324792",
	"lastlogin":"1344399107","lastsend":"0","attachsize":"774822","addsize":"0","addfriend":"0","flag":"0",
	"newpm":"0","avatar":"0","regip":"127.0.0.1","ip":"127000000","mood":"0","quiznum":"27","winnum":"2",
	"lostnum":"0","voternum":"10","isfriend":1}},"count":1},"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>�Ƽ�����б�</h2>
#### ע�⣺ͬ [���Ŵ�����а�ӿ�](#���Ŵ�����а�ӿ�)
capi/space.php?uid=5&do=quiz&page=0&perpage=2&view=hot&m_auth=54f8qnt8HxbRz8NWomy0e4k2gKvVvc6oil8qDY9upUERswmzj17Dt8R%252B652pTEKjHTOgNjgJ80RzLSsp7vbN
#### �������
	* �û�id -- uid
	* �ڼ�ҳ -- page
	* ÿҳ��ʾ����  -- perpage
	* ��ѯ���� -- view, ����Ϊhot
	* API��Կ -- m_auth, �ɵ�¼�󷵻�

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[quizs]������б� ��Ŀ�ֶ�����
			* ���id : quizid
			* ������ĵ��û�id : uid
			* ������ĵ��û��� : username
			* ��ı���: subject
			* �������: viewnum
			* �ظ�������replynum
			* �ȶ�: hot
			* ʱ��: dateline
			* ����������: joincost
			* �������Ͷע����: portion
			* ��ֹʱ��: endtime
			* Ԥ�ƹ������ʱ��: resulttime
			* ���һ��ͶƱʱ��: lastvote
			* �����ĵ�����: voternum
			* ��id: keyoid
			* ��: keyoption
			* �����: totalcost
		* data[count], �����б���Ŀ��, ���ñ���
#### ����
	{"code":0,"data":{"quizs":[{"quizid":"48","topicid":"0","uid":"7","username":"test2","subject":"23123","classid":"0","viewnum":"2","replynum":"0","hot":"2",
	"dateline":"1343974426","pic":"","picflag":"0","noreply":"0","friend":"0","password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0","click_5":"0",
	"joincost":"100","portion":"3","endtime":"1344579220","resulttime":"1344582820","lastvote":"1343974888","voternum":"3","maxchoice":"0","sex":"0","keyoid":"0",
	"keyoption":"","totalcost":"400","hasremind":"0","hasexceed":"0","tag":"","message":"","postip":"127.0.0.1","related":"","relatedtime":"0","target_ids":"",
	"hotuser":"1,5","magiccolor":"0","magicpaper":"0","magiccall":"0","option":["1221","123123"],"invite":"","optioncount":["3","1"]},{"quizid":"49","topicid":"0",
	"uid":"5","username":"summit","subject":"�����Ż�ȯ","classid":"0","viewnum":"1","replynum":"0","hot":"1","dateline":"1344235585","pic":"","picflag":"0",
	"noreply":"0","friend":"0","password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0","click_5":"0","joincost":"20","portion":"3",
	"endtime":"1344235733","resulttime":"1344843977","lastvote":"1344235654","voternum":"2","maxchoice":"0","sex":"0","keyoid":"95","keyoption":"23",
	"totalcost":"120","hasremind":"0","hasexceed":"0","tag":"","message":"","postip":"127.0.0.1","related":"","relatedtime":"0","target_ids":"","hotuser":"1",
	"magiccolor":"0","magicpaper":"0","magiccall":"0","option":["23","2"],"invite":"","optioncount":["4","2"]}],"count":2},"msg":"���ݻ�ȡ�ɹ�",
	"action":"rest_success"}

******************************
<h2>��ȡע����֤��</h2>
capi/do.php?ac=register&op=seccode
#### �������
	* �������� -- op, ����Ϊseccode

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, rest_success:����ɹ�, rest_fail:����ʧ��
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ������������������
		* data[seccode_auth] -- ���ص���֤��key����ע��ʱ��Ҫ����
		* data[seccode] -- ��֤��

#### ����
	{"code":0,"data":{"seccode_auth":"1a6431MIvgvhZZzUPUmCUML%2FtL4rlXrN2R8nL5G3qvta","seccode":"CQ7T"},
	"msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>ע��</h2>
/capi/do.php?ac=register&registersubmit=true&username=test4&password=123&password2=123&seccode=cQ7T&m_auth=1a6431MIvgvhZZzUPUmCUML%2FtL4rlXrN2R8nL5G3qvta
#### �������
	* �������� -- registersubmit, ����Ϊtrue
	* �û��� -- username
	* �û�����ĵ�һ������ -- password
	* �û������ȷ������ -- password2
	* �û��������֤�� -- seccode
	* ������֤�뷵�ص�key -- m_auth

#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�
	* �û��ռ���Ϣ -- space
		* groupid -- �����û��飨����
		* credit -- ���(�������ע�����ӵĽ��)
		* experience -- ����(�������ע�����ӵľ���)
		* username -- �û���
		* name -- ʵ��
		* namestatus -- �Ƿ�ʵ��
		* videostatus -- �Ƿ���Ƶ��֤
		* friendnum -- ������
		* viewnum -- �������
		* notenum -- ֪ͨ��
		* addfriendnum -- ��ע��
		* doingnum -- ������
		* lastpost -- �����ύʱ��
		* lastlogin -- ���µ�¼ʱ��
		* attachsize -- �ռ��С
		* flag -- �Ƿ񱻽�
		* newpm -- �Ƿ�����֪ͨ
		* avatar -- ����ͷ��
		* quiznum -- �����Ĵ����
		* winnum -- Ӯ�Ĵ���
		* lostnum -- ��Ĵ���
		* voternum -- �μӴ�ĵĴ���

#### ����
	{"code":0,"data":{"space":{"uid":"11","sex":"0","email":"test6@betit.cn","newemail":"","emailcheck":"0",
	"mobile":"","qq":"","msn":"","msnrobot":"","msncstatus":"0","videopic":"","birthyear":"0","birthmonth":"0",
	"birthday":"0","blood":"","marry":"0","birthprovince":"","birthcity":"","resideprovince":"","residecity":"",
	"note":"","spacenote":"","authstr":"","theme":"","nocss":"0","menunum":"0","css":"",
	"privacy":{"view":{"index":"0","friend":"0","wall":"0","feed":"0","mtag":"0","event":"0","doing":"0",
	"blog":"0","quiz":"0","album":"0","share":"0","poll":"0"},"feed":{"doing":1,"blog":1,"quiz":1,"joinquiz":1,
	"upload":1,"share":1,"poll":1,"joinpoll":1,"thread":1,"post":1,"mtag":1,"event":1,"join":1,"friend":1,
	"comment":1,"show":1,"credit":1,"spaceopen":1,"invite":1,"task":1,"profile":1,"click":1}},"friend":"",
	"feedfriend":"","sendmail":"","magicstar":"0","magicexpire":"0","timeoffset":"","weibo":"","groupid":"0",
	"credit":"25","experience":"15","username":"test6","name":"","namestatus":"0","videostatus":"0","domain":"",
	"friendnum":"0","viewnum":"0","notenum":"0","addfriendnum":"0","mtaginvitenum":"0","eventinvitenum":"0",
	"myinvitenum":"0","pokenum":"0","doingnum":"0","blognum":"0","albumnum":"0","threadnum":"0","pollnum":"0",
	"eventnum":"0","sharenum":"0","dateline":"1344414070","updatetime":"0","lastsearch":"0","lastpost":"0",
	"lastlogin":"1344414070","lastsend":"0","attachsize":"0","addsize":"0","addfriend":"0","flag":"0","newpm":"0",
	"avatar":"0","regip":"127.0.0.1","ip":"127000000","mood":"0","quiznum":"0","winnum":"0","lostnum":"0",
	"voternum":"0","self":1,"friends":[],"allnotenum":0},
	"m_auth":"cf7chDvDIcnUVeupGp4utLftIQEP%2B1rP8eGrGWydH3ITmly6DURpvHCvByCJlE0hEus%2F5Ji%2FqVUrfnd3dHn6%2BA"},
	"msg":"ע��ɹ��ˣ�������˿ռ�","action":"registered"}
	
<h2>��¼</h2>
capi/do.php?ac=login&username=summit&password=likeyou&loginsubmit=true
#### �������
	* �û��� -- username
	* ���� -- password
	* �ύ���� -- loginsubmit�� ����Ϊtrue
#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�
	* �û��ռ���Ϣ -- space
		* groupid -- �����û��飨����
		* credit -- ���
		* experience -- ����
		* username -- �û���
		* name -- ʵ��
		* namestatus -- �Ƿ�ʵ��
		* videostatus -- �Ƿ���Ƶ��֤
		* friendnum -- ������
		* viewnum -- �������
		* notenum -- ֪ͨ��
		* addfriendnum -- ��ע��
		* doingnum -- ������
		* lastpost -- �����ύʱ��
		* lastlogin -- ���µ�¼ʱ��
		* attachsize -- �ռ��С
		* flag -- �Ƿ񱻽�
		* newpm -- �Ƿ�����֪ͨ
		* avatar -- ����ͷ��
		* quiznum -- �����Ĵ����
		* winnum -- Ӯ�Ĵ���
		* lostnum -- ��Ĵ���
		* voternum -- �μӴ�ĵĴ���
#### ����
	{"code":{"space":{"uid":"1","groupid":"11","credit":"2030","experience":"2030","username":"admin","name":"","namestatus":"0","videostatus":"0","domain":"",
	"friendnum":"0","viewnum":"3","notenum":"0","addfriendnum":"0","doingnum":"0",
	"blognum":"3","albumnum":"0","threadnum":"0","pollnum":"0","eventnum":"0","sharenum":"0","dateline":"1343725030","updatetime":"1343966557","lastsearch":"0",
	"lastpost":"1344324792","lastlogin":"1344328793","attachsize":"774822","addsize":"0","addfriend":"0","flag":"0","newpm":"0","avatar":"0",
	"mood":"0","quiznum":"27","winnum":"2","lostnum":"0","voternum":"10"},
	"m_auth":"55dalDuJytwHteL6s5qlKwHLmhIhpGZ4fZUXHu0"},"data":[],
	"msg":"��¼�ɹ��ˣ����������������¼ǰҳ�� \\1","action":"login_success"}

<h2>�ϴ�ͼƬ</h2>
#### ע��:����POST�ϴ�
#### POST������
	<!DOCTYPE HTML>
	<html>
	<head>
	<meta charset="utf-8">
	<title>�ϴ�ͼƬ</title></head><body>
	<form action="capi/cp.php?ac=upload" method="post" enctype="multipart/form-data">
	<input type="file" name="attach"/><input type="hidden" name="op" value="uploadphoto2" />
	<input type="hidden" name="uid" value="1" />
	<input type="hidden" name="uploadsubmit2"  value="true" />
	<input type="hidden" name="m_auth"  value="af9cCEMpQlfFTifZltugadwhGAXL%2Ba%2BCor8voR9jZyBh60v4xFryq2i" />
	<input type="hidden" name="topicid"  value="0" />
	<input type="hidden" name="ac"  value="upload" />
	<input type="hidden" name="albumid" value="0" />
	<input type="submit"  name="submit"  value="�ύ"/>
	</form>
	</body>
	</html>
#### �������
	* �ϴ��ļ� -- attach
	* ��������(�̶�����) -- op: uploadphoto2, uploadsubmit2:true, topicid:0. albumid:0, ac:upload
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�
	* �ϴ��û�id -- uid
#### �����ֶ�
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ����������һ������
		* data[pic] -- �ϴ��ɹ���ͼƬ���ݣ�������Ŀ����:
			* �ϴ����û�id -- uid
			* �ϴ����û��� -- username
			* �ϴ�ʱ�� -- dateline
			* �ϴ��ļ��� -- filename
			* ͼƬ���� -- title, Ĭ��Ϊ��
			* ͼƬ���� -- type
			* ͼƬ��С -- size
			* ͼƬ������ļ��� -- filepath
			* �Ƿ�����������ͼ -- thumb, 1���������ˣ�0����û��
			* �Ƿ����Զ��ͼ������� -- remote
			* ͼƬid -- picid, <em>��Ҫ</em>�����������ʱ��Ҫ����
			* ͼƬ�����·�� -- pic
#### ����
	{"code":0,"data":{"pic":{"albumid":0,"uid":"1","username":"test6","dateline":"1344415852","filename":"qq����.png","postip":"127.0.0.1","title":"",
	"type":"image\/png","size":165056,"filepath":"1_1344415852h77H.png","thumb":1,"remote":0,"topicid":0,"picid":80,"pic":"attachment\/1_1344415852h77H.png.thumb.jpg"}},
	"msg":"���еĲ��������","action":"do_success"}

<h2>�������</h2>
capi/cp.php?ac=quiz&quizsubmit=true&subject=�ҵĴ��&options[1]=AӮ&options[2]=B��&pics[1]=81&pics[2]=79&joincost=20&portion=3
&endtime=2012-08-15 17:12:12&resulttime=2012-08-16 17:12:12&friend=0&m_auth=af9cCEMpQlfFT

#### �������
	* ��������(�̶�����) -- quizsubmit: true
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�
	* ��ĵı��� -- subject
	* Aѡ������� -- options[1]
	* Bѡ������� -- options[2]
	* Aѡ���ͼƬid -- pics[1]
	* Bѡ���ͼƬid -- pics[2]
	* ÿһ��Ͷע��Ҫ�Ľ���� -- joincost
	* ÿ���û�����������Ͷע���� -- portion
	* ���Ͷע��ֹʱ�� -- endtime(����ʱҪurlencode)
	* ���Ԥ�ƹ�����ʱ�� -- resulttime(����ʱҪurlencode)
	* �Ƿ�ȫվ���� -- frined , Ĭ��0ȫվ����

#### ���ز���
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ����������һ������
		* data[quiz] -- �����ɹ��Ĵ�ģ�������Ŀ����:
			* ��ĵı��� -- subject
			* �Ƿ�ȫվ���� -- frined , Ĭ��0ȫվ����
			* ÿһ��Ͷע��Ҫ�Ľ���� -- joincost
			* ÿ���û�����������Ͷע���� -- portion
			* ���Ͷע��ֹʱ�� -- endtime
			* ���Ԥ�ƹ�����ʱ�� -- resulttime
			* ���id --  quizid
			* �������û�id -- uid
			* �������û��� -- username

#### ����
	{"code":0,"data":{"quiz":{"subject":"�ҵĴ��","classid":0,"friend":0,"password":null,"noreply":0,"joincost":20,"portion":3,
	"endtime":null,"resulttime":null,"picflag":0,"pic":"","hot":0,"topicid":0,"uid":1,"username":"admin","dateline":"1344417374","quizid":55}},
	"msg":"���еĲ��������","action":"do_success"}


<h2>������</h2>
capi/cp.php?ac=quiz&op=vote&votesubmit=true&quizid=55&option[]=108&m_auth=af9cCEMpQlfFTifZlt
#### �������
	* ��������(�̶�����) -- op:vote, votesubmit: true
	* ���id --  quizid
	* Ͷע��ѡ�� -- option[]
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�

#### ���ز���
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼
	* ��� -- data, json����, ����������һ������
		* data[quiz], ������飬������������
			* ���id -- quizid
			* ��������û�id -- uid
			* �����û� -- hotuser
			* ����ʱ�� -- dateline
			* Ͷһע������ -- joincost
			* �û����Ͷע�� -- portion
			* ��ֹͶעʱ�� -- endtime
			* Ԥ�ƹ������ʱ�� -- resulttime
			* ���һ��Ͷעʱ�� -- lastvote
			* ��ǰ�ۼ�Ͷע -- voternum
			* ����� -- totalcost
			* �Ƿ��Ѿ����ѹ� -- hasremind
			* �Ƿ��Ѿ����� -- hasexceed
			* ��ѡ��id -- keyoid
			* �� -- keyoption
			* ѡ������ -- options�������������£�
				* ѡ��id -- oid
				* �������� -- quizid
				* �û�id -- uid
				* ѡ�� -- option, �ı�����
				* ��Ƭid -- picid
				* ��Ƭ·�� -- pic
				* Ͷע���� -- votenum
				* Ͷעռ��Ͷע�ٷֱ� -- percent
#### ����
	{"code":0,"data":{"quiz":{"quizid":"55","uid":"1","tag":"","message":"","postip":"127.0.0.1","related":"","relatedtime":"0","target_ids":"","hotuser":"",
	"magiccolor":"0","magicpaper":"0","magiccall":"0","option":"a:2:{i:0;s:4:\"AӮ\";i:1;s:4:\"B��\";}","invite":"","topicid":"0","username":"admin",
	"subject":"�ҵĴ��","classid":"0","viewnum":"1","replynum":"0","hot":"0","dateline":"1344417374","pic":"","picflag":"0","noreply":"0","friend":"0",
	"password":"","click_1":"0","click_2":"0","click_3":"0","click_4":"0","click_5":"0","joincost":"20","portion":"3","endtime":"0","resulttime":"0",
	"lastvote":"0","voternum":"0","maxchoice":"0","sex":"0","keyoid":"0","keyoption":"","totalcost":"0","hasremind":"1","hasexceed":"1",
	"options":[{"oid":"107","quizid":"55","uid":"1","option":"AӮ","relatedtime":"1344417374","picid":"81","votenum":"0","pic":
	"attachment\/201208\/8\/1_13444161795Gzu.png.thumb.jpg"},{"oid":"108","quizid":"55","uid":"1","option":"B��","relatedtime":"1344417374","picid":"79",
	"votenum":"0","pic":"attachment\/201208\/1\/1_1343816747cmwS.png"}]}},"msg":"���еĲ��������","action":"do_success"}

<h2>׫д����</h2>
capi/cp.php?ac=comment&commentsubmit=true&message=i like you -- summit&idtype=quizid&id=55&m_auth=af9cCEMpQlfFT

#### �������
	* ��������(�̶�����) -- commentsubmit: true
	* ָʾid��������� -- idtype, quizid�����ģ�uid����ռ�, sid�������
	* ���۹�����id -- id
	* �������� -- message
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�

#### ���ز���
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼

#### ����
{"code":0,"data":"do_success","msg":"���ݻ�ȡ�ɹ�","action":"rest_success"}

<h2>����˽��</h2>
capi/cp.php?ac=pm&op=send&touid=0&pmid=0&username=test6&message=���!summit&pmsubmit=true&m_auth=af9cCEMpQlfFTifZltugadwh

#### �������
	* ��������(�̶�����) -- op: send, touid: 0, pmid: 0, pmsubmit: true
	* ���շ����û��� -- username
	* ˽������ -- message
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�

#### ���ز���
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼

#### ����
{"code":0,"data":[],"msg":"���еĲ��������","action":"do_success"}

<h2>�����ǳ�</h2>
cp.php?ac=profile&op=name&name=summit&m_auth=af9cCEMpQlfFTifZltu

#### �������
	* ��������(�̶�����) -- op: name
	* �ǳ� -- name
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�

#### ���ز���
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼

#### ����
{"code":0,"data":[],"msg":"���еĲ��������","action":"do_success"}

<h2>��д����</h2>
capi/cp.php?ac=doing&addsubmit=true&spacenote=true&message=���!summit&m_auth=af9cCEMpQlfFTifZ

#### �������
	* ��������(�̶�����) -- addsubmit: true, spacenote:true
	* �������� -- message
	* API��Կ -- m_auth, ÿ�ε��ýӿڣ���Ҫ�ṩ��key����֤�û�

#### ���ز���
	* ������ -- code, 0:����ɹ��� 1:����ʧ��
	* �������� -- action, login_success:�����¼�ɹ�
	* ������Ϣ -- msg, ��ϸ�μ���¼

#### ����
{"code":0,"data":[],"msg":"���еĲ��������","action":"do_success"}