###
###    Date:2018-08-02
###   Time:11:50 GMT
###  Author:nianhua
###


Ps.算了算了··· 还是写中文吧，谷歌翻译用的要死要死的。</br>
#首先说一下这几个文件是干嘛的：</br>
文件:envirginia.py</br>
&nbsp;&nbsp;就是常规的维吉尼亚加密</br>
文件:devirginia.py</br>
&nbsp;&nbsp;就是常规的维吉尼亚解密</br>
文件:kasiski.py</br>
&nbsp;&nbsp;卡西斯基测试，主要是用来根据密文确定密钥长度的算法，举例如下：</br>
密文：gpeflwhnbsnyytumpylushzaosyrrauyamosbhrtunltigafepwnspxeabinsinraiuhpetqvruutowyfhhdlwuangeaacybvsnvdnajrrxaehnoegspoioyaigousomeatsfbzthuyfbzsbpwoaaiqlligbouhpeomeailohohgphtbqngpgagmrrsutvwnfdctuueadbonzeshclhzefuitgpeqvqnnvdbbnmrvbhanhbaejoiaemsgyogttianulbvgqpmsnbifmceqeigoqhnbtulsaemdbphgjpagmulfmaakqrbvggyuiaqntousswrplxtummgvxozinlvztumsrkyscwnqlhtnvdhzylraszlhhndeolyntciqlxiabocsucrawullegpelmctjpeelnhrzevzwoaaeecutvwnbmynrzgloupcqnrzmaalrrzolgatulmenzegoyfnktbymfbzazlhtntllhhdcpyfpwaytyohfaakeqtunczoipxeqpeuhmhnlenyfyvvsgyocgqoaphsbueipnayuagayrfbhrpgphtsraihndegoyfhbuelzagpeezcnnxofpnibvtbnoiqmaakfiimiajfofmcbuziqmngpulemlnacoaawvabtumiezinfqsgoyrrisbuzoebhvzvobspevzefaibuulrfpryceakeuhmpewvrunozgcbtjlrbefhnifnapacoabhnanhruaafzavtuelmmvafvamdrapbuxeabsnuxdvaenzydvvohyjrraeaaaeamrnacoaeeelhognuakumrvtnsfyvtlspntrltbiutgtejpnhyqfriotgpagabelpaquyvrzbrlhsgirglxrvohgwbyfqcnsfyzmnghflldophnibvaysspugsvjulvvsgyocgwrfioiybmhzwlrbenjbeeafbywequupoosrnuyhhdntsbbmeymsfznusniaaiuaeiyscntjrnphcrtlfmutumrfmoraqsulxtummbuyynaaebfevniaknhnbtupmlnbtryqafibbbnayttuljaemngzxiqnueucsuinqabohohgabifilyzofsqcvlhtgpeelmuybsuhpeomeakypywrnifejisglxeamrtpysqqstbmtswrfaodlqnyphefbhnaheimrnwjenteqtcsqqrrjneqxojllsnvdrebahatrkpitwrvzqhnbiuhpeqiiyfmervfbynwrvtlmcvrgenymaalmbznosbhrzycbvdvacoaaaeluvbqdnifeuwwsyyqhmngsshndevoyaeltullezirxhztrzekwfavviannongohuamnvwuvwazmtbtyapwmcsytrnavsorrehlkcdabmlmutumrflyayttupmoeqwnuneqboqvnhnbdbjnoejugabelaavknhnbiqpxngsnbdgybenzphdfwtulsmnlezlmthlygocntatuhniuitrknhrvtulpigilshwtfehvjbeimrliiyfpohsxenzllouvrkoamcdrvtvhfllinqjbuzuiyfnoylhvtihqwcgvlisqhnkinygkavqngpeflnhvvgfaynlmaezugbehnaudvnfryynguaapqohtdolnoqiyllmaalybblsbvsphhbrvespnfewmlvorrfpryceakesvligpafmirpmdzlnoppagdctubhrtcngpefljatmszfjlnvafvotyqnrkcsgwgvcytumbbfunqgohabtumiamirzitvvhwuqcudclymnnifeuqmgvwoaaeecyhvaeallgvmsvuwrrisrocsiqgbyunqtenyhjhatjoutuqszlhtnteakiwzmnghhdcwwrymaemtulhtbkoajyngzaglopbvtulmepwnfaungtynsfojqntkyvvitvvhsbvllzifnzafabeljrbhxeabhroirvhoazorewuakcntpifcicnbibunhrzensmovamhjbtbaalbjoaxhlzccntcbumeedagpingpefairvvgbmjhlaiphfvvooedbippialgeeoeajcefkaaiycntlrkopbvwvabohbiaqorlbogoywbzkvuacnxighftuqsipnayuagayruisflfdbubrlhtbcculxiabhralavvianifbcrlvotuaaakuszmnjlzialtulgwbzkvuaucbogoylnatqlarrmoswiwrzaakqhrvtulwaytcbtysswrrenrnxojlltumrrpmnbvegoymnvtulhgbmsgvnhrpuzhhdhupcpfegpeelcsawekjosrnoeabifaaqznagmoshzfnqrfabepiuflcsvonbyunpmostunfdighfrraohywefinqoiwgwcbumeedegovolaiuhpeomeahleciiellospuzhhmnkhvuysntlzffismmnjbiamsflhtbctbunhrzonkhogxrbwyrygaqqosgmdgoyyuivriyeazegblnrltbtssuwpnuxwvbhzvmtbntulgipwuykinygpbphtbctplltnqnchltfehvjbwrzejluknvdylntummtvugnqngheiaocnyynbbtbwotgwotyyagisgyuiawngoysrxaeamnbeijhhtlwunsftbatnynohbwvabeimrlwurgjrnphbblynuxsbclrxoaytynkdufbeqhflbntulmazmsgyintuagllintwrsffvbtrknojwrxphpricroupcqnrzmaalhrhftubhrzyfnktbymrxqntphhnzmbusmrinfzocpmsfuimnbtryqhnblvuyybctnryucnoescfrawbyeshqyhlvumiiapunucalpmhv<br>

TIP:各位老铁，这个密文中最后一段是拼音，转成汉字之后输入支付宝口令红包，可以领红包！先到先得哈哈！

````

---------------------------------------------------------------------------------------
 以下是程序示例输出：
---------------------------------------------------------------------------------------
└──╼ $python3 kasiski.py 
请输入密文:gpeflwhnbsnyytumpylushzaosyrrauyamosbhrtunltigafepwnspxeabinsinraiuhpetqvruutowyfhhdlwuangeaacybvsnvdnajrrxaehnoegspoioyaigousomeatsfbzthuyfbzsbpwoaaiqlligbouhpeomeailohohgphtbqngpgagmrrsutvwnfdctuueadbonzeshclhzefuitgpeqvqnnvdbbnmrvbhanhbaejoiaemsgyogttianulbvgqpmsnbifmceqeigoqhnbtulsaemdbphgjpagmulfmaakqrbvggyuiaqntousswrplxtummgvxozinlvztumsrkyscwnqlhtnvdhzylraszlhhndeolyntciqlxiabocsucrawullegpelmctjpeelnhrzevzwoaaeecutvwnbmynrzgloupcqnrzmaalrrzolgatulmenzegoyfnktbymfbzazlhtntllhhdcpyfpwaytyohfaakeqtunczoipxeqpeuhmhnlenyfyvvsgyocgqoaphsbueipnayuagayrfbhrpgphtsraihndegoyfhbuelzagpeezcnnxofpnibvtbnoiqmaakfiimiajfofmcbuziqmngpulemlnacoaawvabtumiezinfqsgoyrrisbuzoebhvzvobspevzefaibuulrfpryceakeuhmpewvrunozgcbtjlrbefhnifnapacoabhnanhruaafzavtuelmmvafvamdrapbuxeabsnuxdvaenzydvvohyjrraeaaaeamrnacoaeeelhognuakumrvtnsfyvtlspntrltbiutgtejpnhyqfriotgpagabelpaquyvrzbrlhsgirglxrvohgwbyfqcnsfyzmnghflldophnibvaysspugsvjulvvsgyocgwrfioiybmhzwlrbenjbeeafbywequupoosrnuyhhdntsbbmeymsfznusniaaiuaeiyscntjrnphcrtlfmutumrfmoraqsulxtummbuyynaaebfevniaknhnbtupmlnbtryqafibbbnayttuljaemngzxiqnueucsuinqabohohgabifilyzofsqcvlhtgpeelmuybsuhpeomeakypywrnifejisglxeamrtpysqqstbmtswrfaodlqnyphefbhnaheimrnwjenteqtcsqqrrjneqxojllsnvdrebahatrkpitwrvzqhnbiuhpeqiiyfmervfbynwrvtlmcvrgenymaalmbznosbhrzycbvdvacoaaaeluvbqdnifeuwwsyyqhmngsshndevoyaeltullezirxhztrzekwfavviannongohuamnvwuvwazmtbtyapwmcsytrnavsorrehlkcdabmlmutumrflyayttupmoeqwnuneqboqvnhnbdbjnoejugabelaavknhnbiqpxngsnbdgybenzphdfwtulsmnlezlmthlygocntatuhniuitrknhrvtulpigilshwtfehvjbeimrliiyfpohsxenzllouvrkoamcdrvtvhfllinqjbuzuiyfnoylhvtihqwcgvlisqhnkinygkavqngpeflnhvvgfaynlmaezugbehnaudvnfryynguaapqohtdolnoqiyllmaalybblsbvsphhbrvespnfewmlvorrfpryceakesvligpafmirpmdzlnoppagdctubhrtcngpefljatmszfjlnvafvotyqnrkcsgwgvcytumbbfunqgohabtumiamirzitvvhwuqcudclymnnifeuqmgvwoaaeecyhvaeallgvmsvuwrrisrocsiqgbyunqtenyhjhatjoutuqszlhtnteakiwzmnghhdcwwrymaemtulhtbkoajyngzaglopbvtulmepwnfaungtynsfojqntkyvvitvvhsbvllzifnzafabeljrbhxeabhroirvhoazorewuakcntpifcicnbibunhrzensmovamhjbtbaalbjoaxhlzccntcbumeedagpingpefairvvgbmjhlaiphfvvooedbippialgeeoeajcefkaaiycntlrkopbvwvabohbiaqorlbogoywbzkvuacnxighftuqsipnayuagayruisflfdbubrlhtbcculxiabhralavvianifbcrlvotuaaakuszmnjlzialtulgwbzkvuaucbogoylnatqlarrmoswiwrzaakqhrvtulwaytcbtysswrrenrnxojlltumrrpmnbvegoymnvtulhgbmsgvnhrpuzhhdhupcpfegpeelcsawekjosrnoeabifaaqznagmoshzfnqrfabepiuflcsvonbyunpmostunfdighfrraohywefinqoiwgwcbumeedegovolaiuhpeomeahleciiellospuzhhmnkhvuysntlzffismmnjbiamsflhtbctbunhrzonkhogxrbwyrygaqqosgmdgoyyuivriyeazegblnrltbtssuwpnuxwvbhzvmtbntulgipwuykinygpbphtbctplltnqnchltfehvjbwrzejluknvdylntummtvugnqngheiaocnyynbbtbwotgwotyyagisgyuiawngoysrxaeamnbeijhhtlwunsftbatnynohbwvabeimrlwurgjrnphbblynuxsbclrxoaytynkdufbeqhflbntulmazmsgyintuagllintwrsffvbtrknojwrxphpricroupcqnrzmaalhrhftubhrzyfnktbymrxqntphhnzmbusmrinfzocpmsfuimnbtryqhnblvuyybctnryucnoescfrawbyeshqyhlvumiiapunucalpmhv
请输入最短相似长度（一般为3或4或更长）3
如果没有找到相似字符串，请降低最短相似长度
如果没有找到相同公因子，请增加最短相似长度
{'gpe': 217, 'pef': 1610, 'efl': 1610, 'hnb': 273, 'bsn': 763, 'nyy': 2611, 'ytu': 1757, 'tum': 315, 'shz': 2335, 'yrr': 637, 'rra': 763, 'mos': 2208, 'osb': 1246, 'sbh': 1246, 'bhr': 525, 'hrt': 1694, 'tun': 469, 'epw': 1876, 'pwn': 1876, 'pxe': 462, 'xea': 714, 'eab': 714, 'abi': 1047, 'rai': 507, 'aiu': 927, 'iuh': 1176, 'uhp': 91, 'hpe': 91, 'vru': 637, 'yfh': 500, 'hhd': 406, 'lwu': 2583, 'wua': 1904, 'eaa': 703, 'bvs': 1578, 'snv': 1120, 'nvd': 126, 'jrr': 686, 'rxa': 2548, 'xae': 2548, 'ehn': 1524, 'noe': 1330, 'oya': 1209, 'igo': 154, 'ous': 196, 'ome': 35, 'mea': 35, 'fbz': 7, 'woa': 273, 'oaa': 273, 'aai': 843, 'iql': 231, 'lli': 1416, 'lig': 1554, 'peo': 973, 'eom': 973, 'oho': 931, 'hoh': 931, 'ohg': 714, 'gph': 394, 'pht': 394, 'htb': 1729, 'qng': 1432, 'ngp': 455, 'agm': 115, 'mrr': 2100, 'utv': 238, 'tvw': 238, 'vwn': 238, 'wnf': 1736, 'nfd': 2195, 'dct': 1533, 'ctu': 1533, 'nze': 259, 'zef': 473, 'fui': 2618, 'uit': 1291, 'tgp': 637, 'peq': 1026, 'vqn': 1386, 'bbn': 840, 'mrv': 588, 'vbh': 2309, 'anh': 504, 'aem': 42, 'msg': 2058, 'sgy': 287, 'gyo': 287, 'ian': 1099, 'bvg': 49, 'pms': 2565, 'snb': 1199, 'nbi': 973, 'bif': 837, 'fmc': 354, 'qhn': 959, 'nbt': 770, 'btu': 368, 'tul': 175, 'uls': 1197, 'bph': 2275, 'pag': 560, 'lfm': 710, 'maa': 144, 'aak': 200, 'akq': 1946, 'gyu': 2331, 'yui': 2200, 'uia': 2331, 'iaq': 1802, 'qnt': 1624, 'ssw': 1946, 'swr': 847, 'lxt': 700, 'xtu': 700, 'umm': 700, 'mgv': 1484, 'zin': 319, 'ysc': 649, 'lht': 126, 'htn': 126, 'szl': 1505, 'zlh': 112, 'lhh': 118, 'hhn': 2443, 'hnd': 203, 'nde': 203, 'lyn': 2328, 'ntc': 1660, 'lxi': 1792, 'xia': 1792, 'iab': 1792, 'abo': 711, 'ocs': 1458, 'csu': 702, 'raw': 2471, 'ull': 938, 'lle': 938, 'egp': 1925, 'elm': 351, 'lmc': 861, 'pee': 182, 'eel': 399, 'lnh': 1204, 'nhr': 329, 'hrz': 871, 'rze': 931, 'evz': 267, 'aae': 375, 'aee': 384, 'eec': 1400, 'nrz': 10, 'glo': 1478, 'lou': 1113, 'oup': 2338, 'upc': 1879, 'pcq': 2338, 'cqn': 2338, 'qnr': 1316, 'rzm': 2338, 'zma': 2338, 'aal': 826, 'rzo': 2034, 'atu': 1043, 'ulm': 1463, 'lme': 1463, 'enz': 318, 'zeg': 2058, 'ego': 112, 'goy': 112, 'oyf': 112, 'yfn': 1111, 'fnk': 2331, 'nkt': 2331, 'ktb': 2331, 'tby': 2331, 'bym': 2331, 'tnt': 1393, 'ntl': 1617, 'hdc': 1400, 'yfp': 1047, 'way': 1764, 'ayt': 574, 'yty': 2219, 'faa': 1843, 'ake': 196, 'eqt': 693, 'euh': 182, 'uhm': 182, 'nle': 959, 'eny': 742, 'fyv': 294, 'yvv': 1413, 'vvs': 392, 'vsg': 392, 'yoc': 392, 'ocg': 392, 'hsb': 1407, 'sbu': 122, 'bue': 36, 'ipn': 1596, 'pna': 1596, 'nay': 518, 'ayu': 1596, 'yua': 1596, 'uag': 1596, 'aga': 301, 'gay': 1596, 'ayr': 1596, 'fbh': 623, 'hrp': 1747, 'deg': 1841, 'uel': 168, 'zag': 1326, 'agp': 1459, 'nxo': 1680, 'nib': 308, 'ibv': 308, 'bvt': 1316, 'tbn': 1943, 'iqm': 21, 'mia': 1169, 'cbu': 1414, 'buz': 42, 'mng': 266, 'mln': 417, 'lna': 1593, 'nac': 161, 'aco': 91, 'coa': 91, 'wva': 1463, 'vab': 1463, 'abt': 1134, 'umi': 1134, 'ezi': 682, 'inf': 2166, 'rri': 1176, 'ris': 1176, 'efa': 1368, 'fai': 1368, 'ibu': 1316, 'rfp': 1001, 'fpr': 1001, 'pry': 1001, 'ryc': 1001, 'yce': 1001, 'cea': 1001, 'eak': 437, 'cbt': 1547, 'lrb': 224, 'rbe': 224, 'hni': 182, 'nif': 418, 'ifn': 1231, 'abh': 1239, 'bhn': 448, 'hna': 448, 'uaa': 903, 'vtu': 764, 'vaf': 995, 'afv': 995, 'vam': 1257, 'nux': 1764, 'dva': 514, 'vae': 1050, 'vvo': 1287, 'voh': 97, 'ohy': 1610, 'aea': 4, 'aaa': 501, 'eam': 357, 'amr': 357, 'mrn': 392, 'rna': 586, 'hog': 1680, 'uak': 1176, 'aku': 1386, 'umr': 198, 'rvt': 441, 'nsf': 70, 'sfy': 70, 'vtl': 435, 'spn': 854, 'rlt': 1694, 'ltb': 1694, 'biu': 404, 'otg': 1778, 'gpa': 854, 'gab': 245, 'abe': 588, 'bel': 588, 'brl': 1295, 'rlh': 1295, 'glx': 273, 'gwb': 1332, 'wby': 1979, 'zmn': 987, 'ngh': 987, 'ghf': 1239, 'hfl': 665, 'fll': 665, 'yss': 1353, 'spu': 1528, 'wrf': 238, 'ben': 524, 'njb': 1519, 'jbe': 581, 'fby': 301, 'ywe': 1442, 'osr': 1372, 'srn': 1372, 'msf': 1491, 'nia': 56, 'cnt': 497, 'jrn': 1694, 'rnp': 1694, 'nph': 1694, 'mut': 392, 'utu': 392, 'mrf': 392, 'ulx': 1148, 'mbu': 1785, 'uyy': 1813, 'yyn': 608, 'knh': 406, 'nhn': 385, 'tup': 364, 'upm': 364, 'btr': 1701, 'try': 1778, 'ryq': 1778, 'ytt': 343, 'ttu': 343, 'lja': 665, 'ngz': 830, 'inq': 476, 'boh': 1015, 'lmu': 279, 'ife': 161, 'isg': 1491, 'sqq': 42, 'rfa': 1190, 'hei': 1427, 'eim': 343, 'imr': 343, 'nte': 679, 'neq': 217, 'xoj': 1064, 'ojl': 1064, 'jll': 1064, 'hat': 637, 'trk': 280, 'twr': 1520, 'wrv': 26, 'iiy': 290, 'iyf': 290, 'yma': 623, 'rzy': 1512, 'ael': 32, 'feu': 504, 'yqh': 1525, 'hmn': 1132, 'ngs': 144, 'ltu': 882, 'lez': 150, 'avv': 833, 'vvi': 594, 'via': 833, 'ngo': 1290, 'goh': 420, 'amn': 1294, 'mnv': 931, 'azm': 1365, 'mtb': 1173, 'tbt': 1155, 'bty': 889, 'orr': 301, 'rre': 878, 'pmo': 962, 'vnh': 875, 'nbd': 30, 'ocn': 1124, 'rkn': 1253, 'hrv': 742, 'tfe': 1057, 'feh': 1057, 'ehv': 1057, 'hvj': 1057, 'vjb': 1057, 'bei': 1129, 'mrl': 1155, 'llo': 891, 'rko': 549, 'koa': 350, 'lin': 1181, 'oyl': 649, 'vli': 112, 'kin': 959, 'iny': 959, 'nyg': 959, 'vvg': 441, 'lma': 39, 'mae': 270, 'yng': 266, 'lno': 63, 'bbl': 1032, 'sbv': 280, 'phh': 1135, 'lvo': 504, 'mir': 77, 'rpm': 571, 'tub': 1064, 'ubh': 1064, 'vot': 441, 'oty': 879, 'unq': 77, 'iam': 683, 'itv': 154, 'tvv': 154, 'vvh': 154, 'ymn': 488, 'wrr': 430, 'byu': 525, 'yun': 525, 'tuq': 273, 'uqs': 273, 'ulh': 399, 'agl': 833, 'opb': 189, 'pbv': 189, 'tyn': 784, 'lzi': 253, 'fab': 399, 'irv': 77, 'ntp': 815, 'bun': 476, 'unh': 476, 'btb': 605, 'tba': 651, 'tcb': 224, 'bum': 371, 'ume': 371, 'mee': 371, 'eed': 371, 'gbm': 242, 'lai': 357, 'ial': 130, 'oea': 253, 'ohb': 567, 'bia': 354, 'bog': 105, 'ogo': 105, 'wbz': 91, 'bzk': 91, 'zkv': 91, 'kvu': 91, 'vua': 91, 'igh': 252, 'hft': 651, 'ftu': 651, 'sfl': 315, 'tbc': 308, 'tua': 547, 'mnj': 260, 'ulg': 336, 'yln': 369, 'wrz': 343, 'llt': 294, 'mnb': 371, 'puz': 133, 'uzh': 133, 'zhh': 133, 'lcs': 42, 'nkh': 38, 'vuy': 392, 'bct': 91, 'bnt': 182, 'ntu': 53, 'nqn': 35, 'wot': 4, 'int': 8}
gpe:{31, 7}
pef:{161, 322, 2, 35, 5, 805, 7, 230, 70, 10, 14, 46, 115, 23}
efl:{161, 322, 2, 35, 5, 805, 7, 230, 70, 10, 14, 46, 115, 23}
hnb:{3, 39, 7, 13, 21, 91}
bsn:{109, 7}
nyy:{373, 7}
ytu:{251, 7}
tum:{3, 35, 5, 7, 105, 9, 45, 15, 21, 63}
shz:{467, 5}
yrr:{49, 91, 13, 7}
rra:{109, 7}
······
省略了
······
----------------------------------------
统计密钥长度可能性:
因子:次数
  7:345      <---------------------------关键信息
  2:241                                 
 14:170                                
  3:164
  4:121
······
省略了
······
130:  1
---------------------------------------------------------------------------------------
 程序输出结束。
---------------------------------------------------------------------------------------
````
 程序的逻辑可以参见注释</br>
 在这个示例里，大致可以看出是<密钥长度为7>
 
文件:friedman.py</br>
&nbsp;&nbsp;使用重合指数法测试密钥长度（Index of Coincidence）</br>
````
---------------------------------------------------------------------------------------
 以下是程序示例输出：
---------------------------------------------------------------------------------------
└──╼ #python3 friedman.py 
请输入密文:gpeflwhnbsnyytumpylushzaosyrrauyamosbhrtunltigafepwnspxeabinsinraiuhpetqvruutowyfhhdlwuangeaacybvsnvdnajrrxaehnoegspoioyaigousomeatsfbzthuyfbzsbpwoaaiqlligbouhpeomeailohohgphtbqngpgagmrrsutvwnfdctuueadbonzeshclhzefuitgpeqvqnnvdbbnmrvbhanhbaejoiaemsgyogttianulbvgqpmsnbifmceqeigoqhnbtulsaemdbphgjpagmulfmaakqrbvggyuiaqntousswrplxtummgvxozinlvztumsrkyscwnqlhtnvdhzylraszlhhndeolyntciqlxiabocsucrawullegpelmctjpeelnhrzevzwoaaeecutvwnbmynrzgloupcqnrzmaalrrzolgatulmenzegoyfnktbymfbzazlhtntllhhdcpyfpwaytyohfaakeqtunczoipxeqpeuhmhnlenyfyvvsgyocgqoaphsbueipnayuagayrfbhrpgphtsraihndegoyfhbuelzagpeezcnnxofpnibvtbnoiqmaakfiimiajfofmcbuziqmngpulemlnacoaawvabtumiezinfqsgoyrrisbuzoebhvzvobspevzefaibuulrfpryceakeuhmpewvrunozgcbtjlrbefhnifnapacoabhnanhruaafzavtuelmmvafvamdrapbuxeabsnuxdvaenzydvvohyjrraeaaaeamrnacoaeeelhognuakumrvtnsfyvtlspntrltbiutgtejpnhyqfriotgpagabelpaquyvrzbrlhsgirglxrvohgwbyfqcnsfyzmnghflldophnibvaysspugsvjulvvsgyocgwrfioiybmhzwlrbenjbeeafbywequupoosrnuyhhdntsbbmeymsfznusniaaiuaeiyscntjrnphcrtlfmutumrfmoraqsulxtummbuyynaaebfevniaknhnbtupmlnbtryqafibbbnayttuljaemngzxiqnueucsuinqabohohgabifilyzofsqcvlhtgpeelmuybsuhpeomeakypywrnifejisglxeamrtpysqqstbmtswrfaodlqnyphefbhnaheimrnwjenteqtcsqqrrjneqxojllsnvdrebahatrkpitwrvzqhnbiuhpeqiiyfmervfbynwrvtlmcvrgenymaalmbznosbhrzycbvdvacoaaaeluvbqdnifeuwwsyyqhmngsshndevoyaeltullezirxhztrzekwfavviannongohuamnvwuvwazmtbtyapwmcsytrnavsorrehlkcdabmlmutumrflyayttupmoeqwnuneqboqvnhnbdbjnoejugabelaavknhnbiqpxngsnbdgybenzphdfwtulsmnlezlmthlygocntatuhniuitrknhrvtulpigilshwtfehvjbeimrliiyfpohsxenzllouvrkoamcdrvtvhfllinqjbuzuiyfnoylhvtihqwcgvlisqhnkinygkavqngpeflnhvvgfaynlmaezugbehnaudvnfryynguaapqohtdolnoqiyllmaalybblsbvsphhbrvespnfewmlvorrfpryceakesvligpafmirpmdzlnoppagdctubhrtcngpefljatmszfjlnvafvotyqnrkcsgwgvcytumbbfunqgohabtumiamirzitvvhwuqcudclymnnifeuqmgvwoaaeecyhvaeallgvmsvuwrrisrocsiqgbyunqtenyhjhatjoutuqszlhtnteakiwzmnghhdcwwrymaemtulhtbkoajyngzaglopbvtulmepwnfaungtynsfojqntkyvvitvvhsbvllzifnzafabeljrbhxeabhroirvhoazorewuakcntpifcicnbibunhrzensmovamhjbtbaalbjoaxhlzccntcbumeedagpingpefairvvgbmjhlaiphfvvooedbippialgeeoeajcefkaaiycntlrkopbvwvabohbiaqorlbogoywbzkvuacnxighftuqsipnayuagayruisflfdbubrlhtbcculxiabhralavvianifbcrlvotuaaakuszmnjlzialtulgwbzkvuaucbogoylnatqlarrmoswiwrzaakqhrvtulwaytcbtysswrrenrnxojlltumrrpmnbvegoymnvtulhgbmsgvnhrpuzhhdhupcpfegpeelcsawekjosrnoeabifaaqznagmoshzfnqrfabepiuflcsvonbyunpmostunfdighfrraohywefinqoiwgwcbumeedegovolaiuhpeomeahleciiellospuzhhmnkhvuysntlzffismmnjbiamsflhtbctbunhrzonkhogxrbwyrygaqqosgmdgoyyuivriyeazegblnrltbtssuwpnuxwvbhzvmtbntulgipwuykinygpbphtbctplltnqnchltfehvjbwrzejluknvdylntummtvugnqngheiaocnyynbbtbwotgwotyyagisgyuiawngoysrxaeamnbeijhhtlwunsftbatnynohbwvabeimrlwurgjrnphbblynuxsbclrxoaytynkdufbeqhflbntulmazmsgyintuagllintwrsffvbtrknojwrxphpricroupcqnrzmaalhrhftubhrzyfnktbymrxqntphhnzmbusmrinfzocpmsfuimnbtryqhnblvuyybctnryucnoescfrawbyeshqyhlvumiiapunucalpmhv
------------------------------
0.04476380889228889
------------------------------
0.044472521739962766
0.04481423518882779
------------------------------
0.04507870029256775
0.044964517004692284
0.044609040731117745
------------------------------
0.04382708244732819
0.04568529863641414
0.04498798864380869
0.04468914150412064
------------------------------
0.044594247330142056
0.044319343098409736
0.0462300528326327
0.04495271449389216
0.04324959670890479
------------------------------
0.04381432182262058
0.04419389066691971
0.04382294838726374
0.045970962983411114
0.04527221124731498
0.04442680791228509
------------------------------
0.06570282251932952                          --->看这里，看过来~，这里最接近英语文本的重合指数 0.0667
0.0642821881097346                           --->因此可以判断出密文长度为7
0.06643315545734503                          --->这个0.0667是怎么算的:P(A)^2 + P(B)^2+……+P(Z)^2 =0.0667
0.06582195162086556                          --->（13/100)x(13/100)+(8/100)x(8/100)+(3/100)x (3/100)...=0.0667
0.06702085145395989
0.06280119419826512
0.06664472601612638
------------------------------
0.0481168026201007
0.04686184784438561
0.04540793682374007
0.04504063298694541
0.04076638965835642
0.044675284702985534
0.043367189904586025
0.04342874730686365
------------------------------
0.04752230026508775
0.04686441825816064
0.04632263307598537
0.04279595015576324
0.04464563862928349
0.04702102803738318
0.044898753894080996
0.0438278816199377
0.04151090342679128
------------------------------

---------------------------------------------------------------------------------------
 程序输出结束。
---------------------------------------------------------------------------------------
````
friedman测试相比kasiski测试更为准确，因此可以结合两种方法。


