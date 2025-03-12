# CC-100-Monolingual-Datasets-from-Web-Crawl-Data


This corpus is an attempt to recreate the dataset used for training <a href="https://www.aclweb.org/anthology/2020.acl-main.747.pdf">XLM-R</a>. This corpus comprises of monolingual data for 100+ languages and also includes data for romanized languages (indicated by *_rom). 
This was constructed using the urls and paragraph indices provided by the <a href="https://github.com/facebookresearch/cc_net">CC-Net repository</a> by processing January-December 2018 Commoncrawl snapshots. 
Each file comprises of documents separated by double-newlines and paragraphs within the same document separated by a newline. 
The data is generated using the open source CC-Net repository. No claims of intellectual property are made on the work of preparation of the corpus.

<h3>References</h3>
Please cite the following if you found the resources in this corpus useful.

<UL>
<LI><b>Unsupervised Cross-lingual Representation Learning at Scale</b>,
<i>Alexis Conneau, Kartikay Khandelwal, Naman Goyal, Vishrav Chaudhary, Guillaume Wenzek, Francisco Guzm&aacute;n, Edouard Grave, Myle Ott, Luke Zettlemoyer, Veselin Stoyanov</i>,
Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics (ACL),
p. 8440-8451, July 2020,
<a href="https://www.aclweb.org/anthology/2020.acl-main.747.pdf">pdf</a>,
<a href="https://www.aclweb.org/anthology/2020.acl-main.747.bib">bib</a>.

<LI><b>CCNet: Extracting High Quality Monolingual Datasets from Web Crawl Data</b>,
<i>Guillaume Wenzek, Marie-Anne Lachaux, Alexis Conneau, Vishrav Chaudhary, Francisco Guzm&aacute;n, Armand Joulin, Edouard Grave</i>,
Proceedings of the 12th Language Resources and Evaluation Conference (LREC),
p. 4003-4012, May 2020,
<a href="https://www.aclweb.org/anthology/2020.lrec-1.494.pdf">pdf</a>,
<a href="https://www.aclweb.org/anthology/2020.lrec-1.494.bib">bib</a>.
</UL>

<h3>Download</h3>

<table cellpadding=5 cellspacing=0 border=1><tr><td>
<a href="af.txt.xz">af</a> Afrikaans (305M)<br>
<a href="am.txt.xz">am</a> Amharic (133M)<br>
<a href="ar.txt.xz">ar</a> Arabic (5.4G)<br>
<a href="as.txt.xz">as</a> Assamese (7.6M)<br>
<a href="az.txt.xz">az</a> Azerbaijani (1.3G)<br>
<a href="be.txt.xz">be</a> Belarusian (692M)<br>
<a href="bg.txt.xz">bg</a> Bulgarian (9.3G)<br>
<a href="bn.txt.xz">bn</a> Bengali (860M)<br>
<a href="bn_rom.txt.xz">bn_rom</a> Bengali Romanized (164M)<br>
<a href="br.txt.xz">br</a> Breton (21M)<br>
<a href="bs.txt.xz">bs</a> Bosnian (18M)<br>
<a href="ca.txt.xz">ca</a> Catalan (2.4G)<br>
<a href="cs.txt.xz">cs</a> Czech (4.4G)<br>
<a href="cy.txt.xz">cy</a> Welsh (179M)<br>
<a href="da.txt.xz">da</a> Danish (12G)<br>
<a href="de.txt.xz">de</a> German (18G)<br>
<a href="el.txt.xz">el</a> Greek (7.4G)<br>
<a href="en.txt.xz">en</a> English (82G)<br>
<a href="eo.txt.xz">eo</a> Esperanto (250M)<br>
<a href="es.txt.xz">es</a> Spanish (14G)<br>
<a href="et.txt.xz">et</a> Estonian (1.7G)<br>
<a href="eu.txt.xz">eu</a> Basque (488M)<br>
<a href="fa.txt.xz">fa</a> Persian (20G)<br>
<a href="ff.txt.xz">ff</a> Fulah (3.1M)<br>
<a href="fi.txt.xz">fi</a> Finnish (15G)<br>
<a href="fr.txt.xz">fr</a> French (14G)<br>
<a href="fy.txt.xz">fy</a> Frisian (38M)<br>
<a href="ga.txt.xz">ga</a> Irish (108M)<br>
<a href="gd.txt.xz">gd</a> Scottish Gaelic (22M)<br>
<a href="gl.txt.xz">gl</a> Galician (708M)<br>
</td><td valign="top">
<a href="gn.txt.xz">gn</a> Guarani (1.5M)<br>
<a href="gu.txt.xz">gu</a> Gujarati (242M)<br>
<a href="ha.txt.xz">ha</a> Hausa (61M)<br>
<a href="he.txt.xz">he</a> Hebrew (6.1G)<br>
<a href="hi.txt.xz">hi</a> Hindi (2.5G)<br>
<a href="hi_rom.txt.xz">hi_rom</a> Hindi Romanized (129M)<br>
<a href="hr.txt.xz">hr</a> Croatian (5.7G)<br>
<a href="ht.txt.xz">ht</a> Haitian (9.1M)<br>
<a href="hu.txt.xz">hu</a> Hungarian (15G)<br>
<a href="hy.txt.xz">hy</a> Armenian (776M)<br>
<a href="id.txt.xz">id</a> Indonesian (36G)<br>
<a href="ig.txt.xz">ig</a> Igbo (6.6M)<br>
<a href="is.txt.xz">is</a> Icelandic (779M)<br>
<a href="it.txt.xz">it</a> Italian (7.8G)<br>
<a href="ja.txt.xz">ja</a> Japanese (15G)<br>
<a href="jv.txt.xz">jv</a> Javanese (37M)<br>
<a href="ka.txt.xz">ka</a> Georgian (1.1G)<br>
<a href="kk.txt.xz">kk</a> Kazakh (889M)<br>
<a href="km.txt.xz">km</a> Khmer (153M)<br>
<a href="kn.txt.xz">kn</a> Kannada (360M)<br>
<a href="ko.txt.xz">ko</a> Korean (14G)<br>
<a href="ku.txt.xz">ku</a> Kurdish (90M)<br>
<a href="ky.txt.xz">ky</a> Kyrgyz (173M)<br>
<a href="la.txt.xz">la</a> Latin (609M)<br>
<a href="lg.txt.xz">lg</a> Ganda (7.3M)<br>
<a href="li.txt.xz">li</a> Limburgish (2.2M)<br>
<a href="ln.txt.xz">ln</a> Lingala (2.3M)<br>
<a href="lo.txt.xz">lo</a> Lao (63M)<br>
<a href="lt.txt.xz">lt</a> Lithuanian (3.4G)<br>
<a href="lv.txt.xz">lv</a> Latvian (2.1G)<br>
</td><td valign="top">
<a href="mg.txt.xz">mg</a> Malagasy (29M)<br>
<a href="mk.txt.xz">mk</a> Macedonian (706M)<br>
<a href="ml.txt.xz">ml</a> Malayalam (831M)<br>
<a href="mn.txt.xz">mn</a> Mongolian (397M)<br>
<a href="mr.txt.xz">mr</a> Marathi (334M)<br>
<a href="ms.txt.xz">ms</a> Malay (2.1G)<br>
<a href="my.txt.xz">my</a> Burmese (46M)<br>
<a href="my_zaw.txt.xz">my_zaw</a> Burmese (Zawgyi) (178M)<br>
<a href="ne.txt.xz">ne</a> Nepali (393M)<br>
<a href="nl.txt.xz">nl</a> Dutch (7.9G)<br>
<a href="no.txt.xz">no</a> Norwegian (13G)<br>
<a href="ns.txt.xz">ns</a> Northern Sotho (1.8M)<br>
<a href="om.txt.xz">om</a> Oromo (11M)<br>
<a href="or.txt.xz">or</a> Oriya (56M)<br>
<a href="pa.txt.xz">pa</a> Punjabi (90M)<br>
<a href="pl.txt.xz">pl</a> Polish (12G)<br>
<a href="ps.txt.xz">ps</a> Pashto (107M)<br>
<a href="pt.txt.xz">pt</a> Portuguese (13G)<br>
<a href="qu.txt.xz">qu</a> Quechua (1.5M)<br>
<a href="rm.txt.xz">rm</a> Romansh (4.8M)<br>
<a href="ro.txt.xz">ro</a> Romanian (16G)<br>
<a href="ru.txt.xz">ru</a> Russian (46G)<br>
<a href="sa.txt.xz">sa</a> Sanskrit (44M)<br>
<a href="si.txt.xz">si</a> Sinhala (452M)<br>
<a href="sc.txt.xz">sc</a> Sardinian (143K)<br>
<a href="sd.txt.xz">sd</a> Sindhi (67M)<br>
<a href="sk.txt.xz">sk</a> Slovak (6.1G)<br>
<a href="sl.txt.xz">sl</a> Slovenian (2.8G)<br>
<a href="so.txt.xz">so</a> Somali (78M)<br>
<a href="sq.txt.xz">sq</a> Albanian (1.3G)<br>
</td><td valign="top">
<a href="sr.txt.xz">sr</a> Serbian (1.5G)<br>
<a href="ss.txt.xz">ss</a> Swati (86K)<br>
<a href="su.txt.xz">su</a> Sundanese (15M)<br>
<a href="sv.txt.xz">sv</a> Swedish (21G)<br>
<a href="sw.txt.xz">sw</a> Swahili (332M)<br>
<a href="ta.txt.xz">ta</a> Tamil (1.3G)<br>
<a href="ta_rom.txt.xz">ta_rom</a> Tamil Romanized (68M)<br>
<a href="te.txt.xz">te</a> Telugu (536M)<br>
<a href="te_rom.txt.xz">te_rom</a> Telugu Romanized (79M)<br>
<a href="th.txt.xz">th</a> Thai (8.7G)<br>
<a href="tl.txt.xz">tl</a> Tagalog (701M)<br>
<a href="tn.txt.xz">tn</a> Tswana (8.0M)<br>
<a href="tr.txt.xz">tr</a> Turkish (5.4G)<br>
<a href="ug.txt.xz">ug</a> Uyghur (46M)<br>
<a href="uk.txt.xz">uk</a> Ukrainian (14G)<br>
<a href="ur.txt.xz">ur</a> Urdu (884M)<br>
<a href="ur_rom.txt.xz">ur_rom</a> Urdu Romanized (141M)<br>
<a href="uz.txt.xz">uz</a> Uzbek (155M)<br>
<a href="vi.txt.xz">vi</a> Vietnamese (28G)<br>
<a href="wo.txt.xz">wo</a> Wolof (3.6M)<br>
<a href="xh.txt.xz">xh</a> Xhosa (25M)<br>
<a href="yi.txt.xz">yi</a> Yiddish (51M)<br>
<a href="yo.txt.xz">yo</a> Yoruba (1.1M)<br>
<a href="zh-Hans.txt.xz">zh-Hans</a> Chinese (Simplified) (14G)<br>
<a href="zh-Hant.txt.xz">zh-Hant</a> Chinese (Traditional) (5.3G)<br>
<a href="zu.txt.xz">zu</a> Zulu (4.3M)<br>
</td></tr></table>

</body></html>
