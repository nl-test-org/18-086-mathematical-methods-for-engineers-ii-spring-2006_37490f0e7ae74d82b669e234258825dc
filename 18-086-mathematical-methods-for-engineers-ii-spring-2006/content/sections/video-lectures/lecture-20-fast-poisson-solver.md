---
about_this_resource_text: ''
course_id: 18-086-mathematical-methods-for-engineers-ii-spring-2006
embedded_media:
- id: Video-YouTube-Stream
  media_location: kyx2QgGkEpc
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Video-YouTube-Stream
  type: Video
  uid: 3e36113afa9cb0b24bdb6426e7cc8a11
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/kyx2QgGkEpc/default.jpg
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3db1a9488a9b586f918d2616925ba5ff
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.086S06/ocw-18.086-24mar2006-220k.mp4
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Video-Internet Archive-MP4
  type: Video
  uid: c5c7c1bd0d3028b00d82a5bd44b41ef1
- id: Audio-InternetArchive-MP3
  media_location: http://www.archive.org/download/MIT18.086S06/ocw-18.086-24mar2006.mp3
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Audio-Internet Archive-MP3
  type: Audio
  uid: d8d84a5aff1543cf32ed70a07f2f2639
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/podcast/lecture-20-fast-poisson-solver/id354869182?i=80690687
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Video-iTunes U-MP4
  type: Video
  uid: c2469b300f84d7186b94b1e6170b22e6
- id: 3Play-3PlayYouTubeid-MP4
  media_location: kyx2QgGkEpc
  parent_uid: 83635a800714eb6d074c245595d42184
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f114dfade7f30b68340dc9f7d6025bb1
- id: kyx2QgGkEpc.srt
  parent_uid: 83635a800714eb6d074c245595d42184
  technical_location: https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-20-fast-poisson-solver/kyx2QgGkEpc.srt
  title: 3play caption file
  type: null
  uid: 64e6ad732d560df6c174554818a92892
- id: kyx2QgGkEpc.pdf
  parent_uid: 83635a800714eb6d074c245595d42184
  technical_location: https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-20-fast-poisson-solver/kyx2QgGkEpc.pdf
  title: 3play pdf file
  type: null
  uid: 9c4d9b1ffa016d913fefa0b761f72c10
- id: Caption-3Play YouTube id-SRT
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ff300f5ad2983320f8c1580c74b75eb9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 83635a800714eb6d074c245595d42184
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 688554c85bc0e77f856a4177089aad7c
inline_embed_id: 96995677lecture20:fastpoissonsolver98714525
layout: video
order_index: null
parent_uid: ae0952f1bf1e6ddfcac1200232d8c3a7
related_resources_text: ''
short_url: lecture-20-fast-poisson-solver
technical_location: https://ocw.mit.edu/courses/mathematics/18-086-mathematical-methods-for-engineers-ii-spring-2006/video-lectures/lecture-20-fast-poisson-solver
template_type: Tabbed
title: 'Lecture 20: Fast Poisson Solver'
transcript: '<p><span m=''390''>The following</span> <span m=''810''>content</span>
  <span m=''1470''>is provided</span> <span m=''1950''>by</span> <span m=''2160''>MIT</span>
  <span m=''2770''>OpenCourseWare</span> <span m=''3580''>under</span> <span m=''3740''>a</span>
  <span m=''3980''>Creative</span> <span m=''4420''>Commons</span> <span m=''4900''>license.</span>
  <span m=''6060''>Additional</span> <span m=''6550''>information</span> <span m=''7160''>about</span>
  <span m=''7350''>our</span> <span m=''7480''>license</span> <span m=''8230''>and</span>
  <span m=''8330''>MIT</span> <span m=''8680''>OpenCourseWare</span> <span m=''9510''>in</span>
  <span m=''9650''>general,</span> <span m=''10490''>is</span> <span m=''10840''>available</span>
  <span m=''11480''>at</span> <span m=''11930''>ocw.mit.edu.</span> </p><p><span m=''17410''>PROFESSOR:
  I</span> <span m=''17560''>thought</span> <span m=''17830''>I</span> <span m=''17880''>would,</span>
  <span m=''18220''>in</span> <span m=''18370''>this</span> <span m=''18580''>last</span>
  <span m=''19000''>lecture</span> <span m=''19330''>before</span> <span m=''19750''>the</span>
  <span m=''19860''>break,</span> <span m=''21160''>speak</span> <span m=''21510''>about</span>
  <span m=''21970''>one</span> <span m=''22470''>specific</span> <span m=''23190''>topic.</span>
  <span m=''26660''>It''s</span> <span m=''26930''>often</span> <span m=''27310''>referred</span>
  <span m=''27780''>to as</span> <span m=''27990''>a</span> <span m=''28070''>Fast</span>
  <span m=''28650''>Poisson</span> <span m=''29170''>Solver,</span> <span m=''30050''>so</span>
  <span m=''31190''>what</span> <span m=''31410''>does</span> <span m=''31520''>Poisson</span>
  <span m=''32050''>mean?</span> <span m=''33920''>Poisson</span> <span m=''34460''>means</span>
  <span m=''34920''>Laplace''s</span> <span m=''35630''>equation.</span> <span m=''36350''>So,</span>
  <span m=''36570''>this</span> <span m=''36800''>is</span> <span m=''36970''>the</span>
  <span m=''37140''>five-point</span> <span m=''38640''>Laplacian,</span> <span m=''39870''>which</span>
  <span m=''40070''>could</span> <span m=''40330''>be</span> <span m=''40560''>some</span>
  <span m=''40880''>other</span> <span m=''42000''>discrete</span> <span m=''42720''>Laplace</span>
  <span m=''43190''>matrix,</span> <span m=''43700''>but</span> <span m=''43950''>let''s</span>
  <span m=''44220''>take</span> <span m=''44470''>the</span> <span m=''44580''>one</span>
  <span m=''44800''>we</span> <span m=''44960''>know.</span> <span m=''46760''>So</span>
  <span m=''46950''>we''re</span> <span m=''47090''>in</span> <span m=''47270''>two</span>
  <span m=''47470''>dimensions,</span> <span m=''48920''>and</span> <span m=''49870''>you</span>
  <span m=''50200''>use</span> <span m=''50560''>the</span> <span m=''50660''>word</span>
  <span m=''51700''>Poission''s</span> <span m=''52280''>name,</span> <span m=''52660''>instead</span>
  <span m=''53040''>of</span> <span m=''53140''>Laplace''s</span> <span m=''53860''>name,</span>
  <span m=''54430''>when</span> <span m=''54760''>there''s</span> <span m=''55030''>a</span>
  <span m=''55550''>non-zero</span> <span m=''56270''>right-hand</span> <span m=''56820''>side.</span>
  <span m=''57560''>So</span> <span m=''57870''>otherwise,</span> <span m=''58370''>it''s</span>
  <span m=''58550''>a</span> <span m=''58640''>Laplace</span> <span m=''59470''>Solver,</span>
  <span m=''59680''>but</span> <span m=''61160''>here</span> <span m=''61370''>Poisson.</span>
  <span m=''62210''>OK.</span> <span m=''62840''>So,</span> <span m=''63080''>remember</span>
  <span m=''63490''>that</span> <span m=''63750''>right-hand</span> <span m=''64290''>side</span>
  <span m=''64720''>comes</span> <span m=''65170''>from</span> <span m=''66250''>maybe</span>
  <span m=''66600''>a</span> <span m=''66710''>right-hand</span> <span m=''67230''>side</span>
  <span m=''68540''>f</span> <span m=''68790''>of</span> <span m=''68900''>xy</span>
  <span m=''69720''>in</span> <span m=''70090''>the</span> <span m=''70240''>differential</span>
  <span m=''70810''>equations,</span> <span m=''71930''>but</span> <span m=''72140''>it</span>
  <span m=''72260''>also</span> <span m=''72660''>comes</span> <span m=''73160''>from</span>
  <span m=''75070''>non-zero</span> <span m=''75900''>boundary</span> <span m=''76360''>conditions,</span>
  <span m=''77280''>because</span> <span m=''77610''>non-zero</span> <span m=''78210''>boundary</span>
  <span m=''78650''>conditions,</span> <span m=''80660''>when</span> <span m=''81180''>the</span>
  <span m=''81310''>five-points</span> <span m=''82870''>hit</span> <span m=''83140''>a</span>
  <span m=''83230''>boundary,</span> <span m=''84230''>that</span> <span m=''84510''>known</span>
  <span m=''84910''>value</span> <span m=''85370''>was</span> <span m=''85750''>moved</span>
  <span m=''86120''>over</span> <span m=''86580''>to</span> <span m=''86740''>the</span>
  <span m=''86820''>right-hand</span> <span m=''87350''>side</span> <span m=''87700''>and</span>
  <span m=''88040''>becomes</span> <span m=''88520''>part</span> <span m=''88800''>of</span>
  <span m=''88890''>f.</span> <span m=''89480''>So</span> <span m=''89690''>f</span>
  <span m=''90500''>comes</span> <span m=''90940''>from</span> <span m=''91900''>the</span>
  <span m=''92620''>non-zero</span> <span m=''93190''>boundary</span> <span m=''93610''>conditions,</span>
  <span m=''94360''>as</span> <span m=''94730''>well</span> <span m=''95070''>as</span>
  <span m=''95370''>the</span> <span m=''95540''>non-zero</span> <span m=''96420''>right-hand</span>
  <span m=''96900''>side.</span> <span m=''97730''>OK.</span> </p><p><span m=''99840''>Important</span>
  <span m=''100380''>problems,</span> <span m=''100970''>but</span> <span m=''101410''>special</span>
  <span m=''102150''>on</span> <span m=''102350''>a</span> <span m=''102450''>square</span>
  <span m=''104000''>or</span> <span m=''104250''>a</span> <span m=''104620''>rectangle</span>
  <span m=''105580''>or</span> <span m=''105820''>a</span> <span m=''105920''>cube</span>
  <span m=''106480''>or</span> <span m=''106770''>a</span> <span m=''106820''>box,</span>
  <span m=''107580''>so</span> <span m=''107810''>we''re</span> <span m=''108410''>speaking</span>
  <span m=''110040''>about</span> <span m=''110580''>special</span> <span m=''111120''>geometry.</span>
  <span m=''113760''>Today</span> <span m=''116230''>as</span> <span m=''117160''>we''ve</span>
  <span m=''117430''>been</span> <span m=''117610''>doing,</span> <span m=''118010''>I''ll</span>
  <span m=''118210''>take</span> <span m=''118550''>the</span> <span m=''118710''>case</span>
  <span m=''119160''>on</span> <span m=''119330''>a</span> <span m=''119430''>square,</span>
  <span m=''120740''>and</span> <span m=''121070''>you</span> <span m=''121190''>will</span>
  <span m=''121280''>see</span> <span m=''121610''>that</span> <span m=''121850''>the</span>
  <span m=''122000''>whole</span> <span m=''122840''>idea</span> <span m=''123460''>would</span>
  <span m=''123970''>not</span> <span m=''124470''>fly,</span> <span m=''125410''>if</span>
  <span m=''125640''>we</span> <span m=''125830''>were</span> <span m=''126640''>on</span>
  <span m=''129660''>an</span> <span m=''129910''>ellipse</span> <span m=''130350''>or</span>
  <span m=''130490''>something</span> <span m=''130910''>like</span> <span m=''131130''>that.</span>
  <span m=''132060''>But</span> <span m=''133840''>a</span> <span m=''133950''>lot</span>
  <span m=''134180''>of</span> <span m=''134360''>problems</span> <span m=''135180''>on</span>
  <span m=''136340''>rectangular</span> <span m=''137040''>domains</span> <span m=''137700''>do</span>
  <span m=''138010''>appear</span> <span m=''138420''>in</span> <span m=''138530''>applications,</span>
  <span m=''140140''>or</span> <span m=''140620''>we</span> <span m=''140810''>could</span>
  <span m=''141060''>use,</span> <span m=''142510''>I</span> <span m=''143020''>hope</span>
  <span m=''143260''>you</span> <span m=''143390''>always</span> <span m=''143790''>think</span>
  <span m=''144060''>now</span> <span m=''144300''>about</span> <span m=''145900''>possible</span>
  <span m=''146400''>preconditioners.</span> <span m=''147370''>Any</span> <span m=''147590''>time</span>
  <span m=''147840''>you</span> <span m=''147930''>have</span> <span m=''148140''>something</span>
  <span m=''148550''>fast,</span> <span m=''149850''>it''s</span> <span m=''150370''>a</span>
  <span m=''150460''>candidate</span> <span m=''151940''>to</span> <span m=''152120''>be</span>
  <span m=''152660''>a</span> <span m=''152730''>preconditioner</span> <span m=''153700''>for</span>
  <span m=''154390''>a</span> <span m=''154540''>real</span> <span m=''154810''>problem.</span>
  <span m=''155890''>The</span> <span m=''156010''>real</span> <span m=''156320''>problem</span>
  <span m=''156830''>might</span> <span m=''157140''>not</span> <span m=''157390''>be</span>
  <span m=''157520''>on</span> <span m=''157670''>a</span> <span m=''157750''>square,</span>
  <span m=''159280''>or</span> <span m=''159700''>the</span> <span m=''159810''>real</span>
  <span m=''160070''>problem</span> <span m=''160530''>might</span> <span m=''160800''>not</span>
  <span m=''161070''>have</span> <span m=''162050''>the</span> <span m=''162170''>constant</span>
  <span m=''162740''>co-efficient</span> <span m=''164140''>that</span> <span m=''164310''>we</span>
  <span m=''165170''>have</span> <span m=''165600''>in</span> <span m=''166780''>the</span>
  <span m=''167080''>Laplacian.</span> <span m=''168710''>In</span> <span m=''168830''>that</span>
  <span m=''169070''>case,</span> <span m=''170310''>you''re</span> <span m=''170520''>not</span>
  <span m=''170760''>solving</span> <span m=''171170''>the</span> <span m=''171680''>exact</span>
  <span m=''172130''>problem,</span> <span m=''172970''>but</span> <span m=''174330''>one</span>
  <span m=''174630''>that</span> <span m=''174780''>could</span> <span m=''174980''>be</span>
  <span m=''175200''>reasonably</span> <span m=''175690''>close</span> <span m=''176020''>to</span>
  <span m=''176140''>it.</span> <span m=''176720''>OK.</span> <span m=''179730''>So</span>
  <span m=''179830''>we''ve</span> <span m=''180000''>discussed</span> <span m=''180560''>the</span>
  <span m=''180680''>solution</span> <span m=''181190''>to</span> <span m=''181270''>this</span>
  <span m=''181480''>problem,</span> <span m=''183240''>and</span> <span m=''183460''>actually</span>
  <span m=''183780''>I</span> <span m=''183880''>have</span> <span m=''184010''>a</span>
  <span m=''184070''>little</span> <span m=''184280''>more</span> <span m=''184460''>to</span>
  <span m=''184580''>say</span> <span m=''184800''>about</span> <span m=''185170''>the</span>
  <span m=''185500''>movie</span> <span m=''186680''>that</span> <span m=''187130''>is</span>
  <span m=''187430''>now</span> <span m=''187850''>on</span> <span m=''187980''>the</span>
  <span m=''188090''>website,</span> <span m=''188640''>because</span> <span m=''188890''>I''m</span>
  <span m=''189310''>quite</span> <span m=''189570''>excited</span> <span m=''190090''>about</span>
  <span m=''190300''>that</span> <span m=''190480''>movie.</span> <span m=''194320''>I''ll</span>
  <span m=''194550''>come</span> <span m=''194850''>to</span> <span m=''194960''>the</span>
  <span m=''195060''>movie</span> <span m=''195370''>in</span> <span m=''195500''>a</span>
  <span m=''195580''>second.</span> </p><p><span m=''196050''>Let</span> <span m=''196200''>me</span>
  <span m=''196360''>just</span> <span m=''196770''>say</span> <span m=''197020''>what</span>
  <span m=''197290''>today''s</span> <span m=''197700''>lecture</span> <span m=''198090''>would</span>
  <span m=''198290''>be.</span> <span m=''200830''>The</span> <span m=''201490''>key</span>
  <span m=''201770''>idea</span> <span m=''202210''>here</span> <span m=''203160''>is</span>
  <span m=''204400''>that</span> <span m=''204660''>the</span> <span m=''204840''>eigenvalues</span>
  <span m=''205850''>and</span> <span m=''206000''>eigenvectors</span> <span m=''206750''>of</span>
  <span m=''206860''>this</span> <span m=''207810''>giant</span> <span m=''208240''>matrix</span>
  <span m=''209570''>of</span> <span m=''209730''>order</span> <span m=''210070''>n</span>
  <span m=''210320''>squared</span> <span m=''210640''>by</span> <span m=''210860''>n</span>
  <span m=''211010''>squared,</span> <span m=''211630''>sizes</span> <span m=''212350''>n</span>
  <span m=''212570''>squared</span> <span m=''212820''>by</span> <span m=''212980''>n</span>
  <span m=''213160''>squared.</span> <span m=''214690''>The</span> <span m=''214920''>eigenvalues</span>
  <span m=''215670''>and</span> <span m=''215820''>the</span> <span m=''215900''>eigenvectors</span>
  <span m=''216630''>are</span> <span m=''216770''>known.</span> <span m=''217380''>First</span>
  <span m=''217660''>of</span> <span m=''217730''>all,</span> <span m=''217880''>they''re</span>
  <span m=''218050''>known.</span> <span m=''220270''>The</span> <span m=''220420''>eigenvectors</span>
  <span m=''221320''>are</span> <span m=''221450''>nice</span> <span m=''222330''>discrete</span>
  <span m=''223080''>sine</span> <span m=''223710''>functions;</span> <span m=''224340''>they''re</span>
  <span m=''224560''>sines,</span> <span m=''225200''>because</span> <span m=''225610''>I''m</span>
  <span m=''225800''>assuming</span> <span m=''230080''>they</span> <span m=''230320''>come</span>
  <span m=''230580''>to</span> <span m=''230680''>zero</span> <span m=''231030''>at</span>
  <span m=''231130''>the</span> <span m=''231270''>boundary;</span> <span m=''232350''>so
  that''s</span> <span m=''232610''>why</span> <span m=''232770''>I</span> <span m=''232800''>have</span>
  <span m=''232950''>a</span> <span m=''233020''>sine,</span> <span m=''233550''>rather</span>
  <span m=''233880''>than</span> <span m=''234060''>a</span> <span m=''234160''>cosine.</span>
  <span m=''236410''>First</span> <span m=''236720''>they''re</span> <span m=''236870''>known,</span>
  <span m=''237590''>and</span> <span m=''237770''>second</span> <span m=''239980''>we</span>
  <span m=''240260''>can</span> <span m=''241090''>work</span> <span m=''241610''>with</span>
  <span m=''241820''>them</span> <span m=''242170''>very</span> <span m=''242510''>quickly,</span>
  <span m=''242990''>using</span> <span m=''243410''>the</span> <span m=''243540''>FFT.</span>
  <span m=''245680''>So</span> <span m=''246580''>the</span> <span m=''247220''>point</span>
  <span m=''247580''>is</span> <span m=''247790''>that</span> <span m=''248410''>it''s</span>
  <span m=''248630''>quite</span> <span m=''249240''>exceptional;</span> <span m=''250710''>in</span>
  <span m=''250830''>fact,</span> <span m=''251180''>I</span> <span m=''251720''>don''t</span>
  <span m=''251930''>think</span> <span m=''252150''>I</span> <span m=''252250''>know</span>
  <span m=''252480''>any</span> <span m=''253500''>comparable</span> <span m=''254090''>example,</span>
  <span m=''255290''>in</span> <span m=''255500''>which</span> <span m=''255810''>a</span>
  <span m=''255890''>linear</span> <span m=''256380''>system</span> <span m=''256940''>is</span>
  <span m=''257130''>solved</span> <span m=''257580''>by</span> <span m=''257730''>using</span>
  <span m=''258190''>the</span> <span m=''258270''>eigenvalues</span> <span m=''258990''>and</span>
  <span m=''259150''>eigenvectors.</span> <span m=''261100''>Usually</span> <span
  m=''262460''>eigenvalues</span> <span m=''263200''>and</span> <span m=''263490''>eigenvectors,</span>
  <span m=''263870''>they</span> <span m=''264060''>pay</span> <span m=''264370''>off</span>
  <span m=''264740''>for</span> <span m=''265630''>differential</span> <span m=''266170''>equations</span>
  <span m=''266810''>that</span> <span m=''266930''>are</span> <span m=''267000''>growing</span>
  <span m=''267460''>in</span> <span m=''267650''>time.</span> <span m=''269160''>Then</span>
  <span m=''269450''>it</span> <span m=''269570''>is</span> <span m=''269780''>worth</span>
  <span m=''270150''>computing</span> <span m=''270770''>them,</span> <span m=''271030''>because</span>
  <span m=''271380''>then</span> <span m=''271610''>you</span> <span m=''271750''>can</span>
  <span m=''271940''>just</span> <span m=''272170''>multiply</span> <span m=''272670''>by</span>
  <span m=''272950''>either</span> <span m=''273260''>the</span> <span m=''273400''>lamda</span>
  <span m=''273850''>t,</span> <span m=''274260''>and</span> <span m=''274420''>you</span>
  <span m=''274550''>know</span> <span m=''274730''>what''s</span> <span m=''275020''>happening</span>
  <span m=''275440''>later.</span> <span m=''278600''>Eigenvectors,</span> <span m=''279580''>eigenvalues</span>
  <span m=''280100''>have</span> <span m=''280260''>other</span> <span m=''280490''>purposes,</span>
  <span m=''281550''>but</span> <span m=''281820''>very,</span> <span m=''282380''>very</span>
  <span m=''282860''>rarely</span> <span m=''283420''>are</span> <span m=''283610''>they</span>
  <span m=''283730''>used</span> <span m=''284080''>to</span> <span m=''284240''>solve</span>
  <span m=''284540''>a</span> <span m=''284680''>linear</span> <span m=''284950''>system.</span>
  <span m=''286230''>I</span> <span m=''286330''>mean,</span> <span m=''286520''>it''s</span>
  <span m=''286720''>usually</span> <span m=''287210''>far</span> <span m=''287580''>more</span>
  <span m=''287820''>work.</span> <span m=''289360''>And</span> <span m=''289540''>of</span>
  <span m=''289620''>course,</span> <span m=''289870''>it</span> <span m=''289990''>would</span>
  <span m=''290230''>be</span> <span m=''290450''>incredibly</span> <span m=''291110''>more</span>
  <span m=''291390''>work</span> <span m=''291800''>if</span> <span m=''291960''>we</span>
  <span m=''292090''>had</span> <span m=''292290''>to</span> <span m=''292400''>find</span>
  <span m=''292780''>the</span> <span m=''292860''>eigenvalues</span> <span m=''293480''>and</span>
  <span m=''293630''>eigenvectors,</span> <span m=''294380''>but</span> <span m=''294570''>for</span>
  <span m=''294710''>this</span> <span m=''294930''>problem</span> <span m=''295530''>we</span>
  <span m=''295670''>know</span> <span m=''295860''>them.</span> </p><p><span m=''297160''>And</span>
  <span m=''297400''>it</span> <span m=''297460''>also</span> <span m=''297850''>would</span>
  <span m=''298000''>be</span> <span m=''298120''>incredibly</span> <span m=''298690''>more</span>
  <span m=''298910''>work</span> <span m=''299310''>if</span> <span m=''300190''>the</span>
  <span m=''300320''>matrix</span> <span m=''301010''>of</span> <span m=''301170''>eigenvectors,</span>
  <span m=''303370''>the</span> <span m=''303480''>basis</span> <span m=''304020''>matrix,</span>
  <span m=''305130''>the</span> <span m=''305770''>key</span> <span m=''306040''>matrix</span>
  <span m=''306700''>that</span> <span m=''306840''>I''ll</span> <span m=''307280''>denote</span>
  <span m=''307660''>by</span> <span m=''308070''>s --</span> <span m=''309600''>so</span>
  <span m=''309850''>the</span> <span m=''309970''>eigenvectors</span> <span m=''310800''>go</span>
  <span m=''311000''>in</span> <span m=''311130''>a</span> <span m=''311200''>matrix</span>
  <span m=''311880''>s;</span> <span m=''312850''>the</span> <span m=''313060''>eigenvalues</span>
  <span m=''313900''>go</span> <span m=''314130''>in</span> <span m=''314250''>a</span>
  <span m=''314330''>matrix</span> <span m=''315030''>capital</span> <span m=''315550''>lambda;</span>
  <span m=''317430''>so</span> <span m=''317610''>we</span> <span m=''317750''>know</span>
  <span m=''318000''>lambda.</span> <span m=''319000''>It''s</span> <span m=''319290''>going
  to</span> <span m=''319540''>be</span> <span m=''319630''>a</span> <span m=''319710''>simple</span>
  <span m=''320070''>matrix,</span> <span m=''320640''>just</span> <span m=''320940''>diagonal,</span>
  <span m=''322350''>got</span> <span m=''322570''>those</span> <span m=''322790''>n</span>
  <span m=''323260''>numbers</span> <span m=''324160''>and</span> <span m=''324410''>n
  squared</span> <span m=''324740''>numbers,</span> <span m=''325160''>I</span> <span
  m=''325240''>guess,</span> <span m=''325520''>because</span> <span m=''325750''>we''re</span>
  <span m=''326000''>of</span> <span m=''326120''>size</span> <span m=''326740''>n</span>
  <span m=''326950''>squared.</span> <span m=''328160''>But</span> <span m=''328510''>these</span>
  <span m=''328840''>eigenvectors</span> <span m=''329720''>we know.</span> <span
  m=''331570''>So</span> <span m=''331750''>we</span> <span m=''331870''>know</span>
  <span m=''332170''>them,</span> <span m=''332590''>and</span> <span m=''333550''>we
  can</span> <span m=''334430''>compute</span> <span m=''334960''>quickly</span> <span
  m=''335390''>with</span> <span m=''335600''>them,</span> <span m=''335870''>using</span>
  <span m=''336290''>the</span> <span m=''336400''>FFT,</span> <span m=''337910''>or</span>
  <span m=''338100''>using,</span> <span m=''339140''>you</span> <span m=''339300''>might</span>
  <span m=''339610''>want</span> <span m=''339780''>me</span> <span m=''339880''>to</span>
  <span m=''339980''>say,</span> <span m=''340270''>fast</span> <span m=''341100''>sine</span>
  <span m=''341550''>transform,</span> <span m=''343490''>discrete</span> <span m=''344040''>sine</span>
  <span m=''344510''>transform,</span> <span m=''345210''>rather</span> <span m=''345610''>than</span>
  <span m=''346480''>Fourier</span> <span m=''347030''>transform,</span> <span m=''347740''>which</span>
  <span m=''348180''>we</span> <span m=''348350''>think</span> <span m=''348680''>of</span>
  <span m=''348870''>as</span> <span m=''349220''>doing</span> <span m=''349540''>the</span>
  <span m=''349690''>complex</span> <span m=''350270''>exponential.</span> <span m=''352400''>So</span>
  <span m=''352620''>this</span> <span m=''352820''>is</span> <span m=''353000''>a</span>
  <span m=''353150''>small</span> <span m=''354850''>special</span> <span m=''356290''>fast</span>
  <span m=''356790''>Fourier</span> <span m=''357190''>world.</span> <span m=''358890''>It''s</span>
  <span m=''359040''>a</span> <span m=''359280''>special</span> <span m=''359810''>fast</span>
  <span m=''360130''>Fourier</span> <span m=''360510''>world,</span> <span m=''361080''>in</span>
  <span m=''361260''>which</span> <span m=''361610''>the</span> <span m=''361820''>FFT</span>
  <span m=''362710''>and</span> <span m=''363190''>the</span> <span m=''363740''>related</span>
  <span m=''364400''>sine</span> <span m=''364750''>and</span> <span m=''364920''>cosine</span>
  <span m=''367690''>give</span> <span m=''367920''>us</span> <span m=''368340''>a</span>
  <span m=''368470''>quick</span> <span m=''368790''>answer,</span> <span m=''370700''>faster</span>
  <span m=''371260''>than</span> <span m=''371860''>elimination,</span> <span m=''373290''>because</span>
  <span m=''373640''>you</span> <span m=''373960''>all</span> <span m=''374330''>know,</span>
  <span m=''374610''>it''s</span> <span m=''375150''>n</span> <span m=''375530''>log
  n,</span> <span m=''376240''>if</span> <span m=''376400''>n</span> <span m=''376660''>is</span>
  <span m=''376800''>the</span> <span m=''376930''>number</span> <span m=''377330''>of</span>
  <span m=''378010''>Fourier</span> <span m=''378930''>components,</span> <span m=''379970''>and</span>
  <span m=''380340''>that''s</span> <span m=''381380''>hard</span> <span m=''381630''>to</span>
  <span m=''381720''>beat.</span> </p><p><span m=''383490''>Then</span> <span m=''383930''>I''ll</span>
  <span m=''384330''>mention</span> <span m=''384820''>also,</span> <span m=''385970''>for</span>
  <span m=''386090''>this</span> <span m=''386320''>same</span> <span m=''386610''>problem,</span>
  <span m=''388170''>there</span> <span m=''388330''>is</span> <span m=''388470''>another</span>
  <span m=''388860''>way</span> <span m=''389140''>in</span> <span m=''389240''>which</span>
  <span m=''389590''>it</span> <span m=''391050''>can</span> <span m=''391290''>be</span>
  <span m=''391460''>simplified.</span> <span m=''393640''>It''s</span> <span m=''393810''>not</span>
  <span m=''394150''>a</span> <span m=''394290''>Fourier</span> <span m=''394650''>way,</span>
  <span m=''395190''>just</span> <span m=''395470''>a</span> <span m=''395630''>direct</span>
  <span m=''399350''>combining</span> <span m=''401230''>neighboring</span> <span
  m=''402100''>equations,</span> <span m=''402750''>so</span> <span m=''403060''>that''ll</span>
  <span m=''403340''>be</span> <span m=''403440''>number</span> <span m=''403740''>two.</span>
  <span m=''404260''>OK,</span> <span m=''404770''>but</span> <span m=''404960''>mostly</span>
  <span m=''405400''>the</span> <span m=''405550''>lecture</span> <span m=''405950''>is</span>
  <span m=''406060''>about</span> <span m=''406410''>number</span> <span m=''406670''>one.</span>
  <span m=''409670''>The</span> <span m=''411040''>best</span> <span m=''411380''>example</span>
  <span m=''411940''>I</span> <span m=''412060''>know</span> <span m=''412340''>in</span>
  <span m=''412460''>which</span> <span m=''412700''>you</span> <span m=''412810''>would</span>
  <span m=''413040''>use</span> <span m=''413250''>eigenvectors/eigenvalues</span>
  <span m=''414770''>to</span> <span m=''414930''>solve</span> <span m=''416220''>an</span>
  <span m=''416380''>ordinary</span> <span m=''416940''>linear</span> <span m=''417310''>system,</span>
  <span m=''418490''>and</span> <span m=''418720''>I''ll</span> <span m=''418870''>say</span>
  <span m=''419730''>in</span> <span m=''420030''>a</span> <span m=''420100''>word</span>
  <span m=''420420''>just</span> <span m=''420610''>how</span> <span m=''421210''>you</span>
  <span m=''421370''>do</span> <span m=''421550''>it,</span> <span m=''422150''>and</span>
  <span m=''422370''>then</span> <span m=''423140''>what</span> <span m=''423420''>these</span>
  <span m=''423680''>eigenvectors</span> <span m=''424000''>are.</span> <span m=''424750''>OK.</span>
  </p><p><span m=''428030''>Pause.</span> <span m=''429180''>Time</span> <span m=''429450''>out</span>
  <span m=''429840''>to</span> <span m=''430020''>say</span> <span m=''430230''>something</span>
  <span m=''430660''>about</span> <span m=''431180''>the</span> <span m=''431310''>movie.</span>
  <span m=''432330''>So</span> <span m=''432540''>that</span> <span m=''432850''>movie</span>
  <span m=''433310''>that''s</span> <span m=''433620''>now</span> <span m=''433990''>on</span>
  <span m=''434120''>the</span> <span m=''434220''>website</span> <span m=''438200''>does</span>
  <span m=''439730''>sparse</span> <span m=''440180''>elimination,</span> <span m=''442500''>and</span>
  <span m=''443140''>the</span> <span m=''443370''>example</span> <span m=''444310''>it</span>
  <span m=''444490''>takes</span> <span m=''445060''>is</span> <span m=''445510''>k2d,</span>
  <span m=''447150''>and</span> <span m=''447420''>you</span> <span m=''447580''>can</span>
  <span m=''447770''>make</span> <span m=''448060''>it</span> <span m=''449380''>8</span>
  <span m=''449620''>squared</span> <span m=''449980''>by</span> <span m=''450160''>8</span>
  <span m=''450370''>squared,</span> <span m=''450700''>10</span> <span m=''451060''>squared</span>
  <span m=''451310''>by</span> <span m=''451470''>10</span> <span m=''451800''>squared,</span>
  <span m=''452070''>20</span> <span m=''452440''>squared</span> <span m=''452790''>by</span>
  <span m=''452960''>20</span> <span m=''453390''>squared,</span> <span m=''454780''>because</span>
  <span m=''455230''>it</span> <span m=''455410''>shows</span> <span m=''456310''>the</span>
  <span m=''457640''>order</span> <span m=''458170''>that</span> <span m=''458400''>the</span>
  <span m=''458570''>nodes</span> <span m=''458960''>are</span> <span m=''459090''>eliminated</span>
  <span m=''460490''>and</span> <span m=''461190''>the</span> <span m=''461320''>graphs</span>
  <span m=''462390''>of</span> <span m=''464830''>non-zero''s</span> <span m=''465630''>in</span>
  <span m=''465740''>the</span> <span m=''465820''>matrix.</span> <span m=''467040''>It''s</span>
  <span m=''467860''>a</span> <span m=''467950''>bit</span> <span m=''468110''>slow.</span>
  <span m=''469560''>If</span> <span m=''469760''>you</span> <span m=''469920''>do</span>
  <span m=''470140''>20</span> <span m=''470490''>by</span> <span m=''470710''>20,</span>
  <span m=''471090''>you</span> <span m=''471290''>have</span> <span m=''471510''>to</span>
  <span m=''472130''>go</span> <span m=''472300''>away</span> <span m=''472530''>for</span>
  <span m=''474800''>lunch,</span> <span m=''475900''>well</span> <span m=''476070''>maybe</span>
  <span m=''476330''>not</span> <span m=''476590''>lunch,</span> <span m=''476900''>but</span>
  <span m=''477110''>at</span> <span m=''477230''>least</span> <span m=''478070''>coffee</span>
  <span m=''480170''>before</span> <span m=''480600''>it''s</span> <span m=''480790''>done,</span>
  <span m=''481390''>but</span> <span m=''481600''>when</span> <span m=''481810''>it''s</span>
  <span m=''482030''>done,</span> <span m=''482520''>it</span> <span m=''483470''>counts</span>
  <span m=''484020''>the</span> <span m=''484170''>number</span> <span m=''484760''>of
  --</span> <span m=''485740''>it</span> <span m=''485880''>shows</span> <span m=''486530''>the</span>
  <span m=''488970''>non-zero''s</span> <span m=''490020''>that</span> <span m=''490390''>are</span>
  <span m=''490700''>in</span> <span m=''491830''>the</span> <span m=''494160''>elimination</span>
  <span m=''494920''>in</span> <span m=''495050''>the</span> <span m=''495160''>factor</span>
  <span m=''495640''>l</span> <span m=''496070''>from</span> <span m=''496230''>elimination,</span>
  <span m=''497930''>and</span> <span m=''498490''>it</span> <span m=''498630''>counts</span>
  <span m=''499100''>the</span> <span m=''499230''>number</span> <span m=''499510''>of</span>
  <span m=''499600''>non-zero''s,</span> <span m=''500750''>and</span> <span m=''501330''>I</span>
  <span m=''501410''>was</span> <span m=''501590''>just</span> <span m=''501820''>talking</span>
  <span m=''502270''>to</span> <span m=''503000''>Persson</span> <span m=''503480''>about</span>
  <span m=''503830''>also</span> <span m=''504190''>getting</span> <span m=''504580''>it</span>
  <span m=''504730''>to</span> <span m=''504870''>count</span> <span m=''505250''>the</span>
  <span m=''505370''>number</span> <span m=''505800''>of</span> <span m=''506140''>actual</span>
  <span m=''506660''>[? flops ?].</span> </p><p><span m=''509810''>Well,</span> <span
  m=''511880''>why</span> <span m=''511950''>am</span> <span m=''512060''>I</span>
  <span m=''512210''>interested?</span> <span m=''513610''>I''m</span> <span m=''513780''>interested,</span>
  <span m=''514240''>because</span> <span m=''515230''>I</span> <span m=''515380''>don''t</span>
  <span m=''515690''>know</span> <span m=''516970''>what</span> <span m=''520270''>power</span>
  <span m=''520620''>of</span> <span m=''520780''>n</span> <span m=''521170''>those</span>
  <span m=''521540''>numbers</span> <span m=''521980''>are</span> <span m=''522100''>going</span>
  <span m=''522430''>there.</span> <span m=''523960''>I</span> <span m=''524140''>don''t</span>
  <span m=''524390''>know</span> <span m=''524530''>whether</span> <span m=''524940''>the</span>
  <span m=''525130''>number</span> <span m=''525480''>of</span> <span m=''525630''>non-zero''s,</span>
  <span m=''526450''>and</span> <span m=''526590''>I</span> <span m=''526660''>did</span>
  <span m=''526960''>10,</span> <span m=''527350''>20,</span> <span m=''527800''>30,</span>
  <span m=''529100''>and</span> <span m=''529640''>it</span> <span m=''529860''>looked</span>
  <span m=''530310''>not</span> <span m=''530920''>too</span> <span m=''531180''>far</span>
  <span m=''531820''>from</span> <span m=''532200''>the</span> <span m=''532360''>power</span>
  <span m=''536120''>capital</span> <span m=''536530''>n</span> <span m=''536730''>cubed,</span>
  <span m=''539940''>but</span> <span m=''541940''>the</span> <span m=''542070''>notes</span>
  <span m=''542480''>say</span> <span m=''543190''>for</span> <span m=''543600''>nested</span>
  <span m=''544250''>dissection,</span> <span m=''545240''>which</span> <span m=''545450''>would</span>
  <span m=''545620''>be</span> <span m=''545730''>another</span> <span m=''546450''>ordering</span>
  <span m=''548980''>n</span> <span m=''549220''>squared</span> <span m=''549510''>log</span>
  <span m=''549830''>n.</span> <span m=''550330''>So,</span> <span m=''555540''>and</span>
  <span m=''555950''>of</span> <span m=''556030''>course,</span> <span m=''556700''>what</span>
  <span m=''557020''>power</span> <span m=''557360''>we</span> <span m=''557520''>get</span>
  <span m=''557740''>depends</span> <span m=''558210''>on</span> <span m=''558460''>what</span>
  <span m=''558980''>algorithm</span> <span m=''559560''>we</span> <span m=''559670''>use</span>
  <span m=''559960''>for</span> <span m=''560100''>ordering,</span> <span m=''560570''>so</span>
  <span m=''560710''>nested</span> <span m=''561100''>dissection</span> <span m=''561740''>is</span>
  <span m=''561890''>one</span> <span m=''562470''>ordering,</span> <span m=''563250''>which</span>
  <span m=''564280''>hopefully</span> <span m=''564750''>we</span> <span m=''564870''>could</span>
  <span m=''565030''>put</span> <span m=''565240''>into</span> <span m=''565490''>another</span>
  <span m=''565830''>movie.</span> <span m=''568700''>The</span> <span m=''569010''>movie</span>
  <span m=''569460''>now</span> <span m=''569880''>has</span> <span m=''571750''>exact</span>
  <span m=''572670''>minimum</span> <span m=''573440''>degree,</span> <span m=''574110''>real</span>
  <span m=''574720''>MMD,</span> <span m=''575390''>which</span> <span m=''578480''>takes</span>
  <span m=''578900''>as</span> <span m=''579140''>the</span> <span m=''579270''>next</span>
  <span m=''579680''>node</span> <span m=''580830''>the</span> <span m=''581040''>one</span>
  <span m=''581520''>with</span> <span m=''582490''>absolutely</span> <span m=''583240''>the</span>
  <span m=''583340''>minimum</span> <span m=''583790''>degree,</span> <span m=''584160''>not</span>
  <span m=''584410''>just</span> <span m=''584660''>close</span> <span m=''584980''>to</span>
  <span m=''585110''>it.</span> <span m=''586670''>Anyway</span> <span m=''588740''>have</span>
  <span m=''588870''>a</span> <span m=''588950''>look</span> <span m=''589230''>at</span>
  <span m=''589350''>that</span> <span m=''590140''>movie,</span> <span m=''591580''>and</span>
  <span m=''592860''>if</span> <span m=''593040''>you</span> <span m=''593200''>have</span>
  <span m=''593860''>any</span> <span m=''594110''>interest,</span> <span m=''596760''>see</span>
  <span m=''600130''>how</span> <span m=''600300''>the</span> <span m=''600700''>count</span>
  <span m=''601060''>increases</span> <span m=''601780''>as</span> <span m=''602030''>n</span>
  <span m=''602290''>increases,</span> <span m=''603510''>and</span> <span m=''603970''>also</span>
  <span m=''605180''>you</span> <span m=''605360''>could</span> <span m=''606250''>change,</span>
  <span m=''606730''>slightly</span> <span m=''607130''>adapt,</span> <span m=''607720''>the</span>
  <span m=''608520''>algorithm</span> <span m=''609800''>that</span> <span m=''610590''>creates</span>
  <span m=''611150''>the</span> <span m=''611280''>ordering,</span> <span m=''611630''>creates</span>
  <span m=''612210''>the</span> <span m=''612310''>permutation</span> <span m=''613400''>and</span>
  <span m=''613560''>see</span> <span m=''613780''>what</span> <span m=''614120''>happens</span>
  <span m=''614440''>there.</span> <span m=''615370''>There''s</span> <span m=''615860''>a</span>
  <span m=''615950''>lot</span> <span m=''616230''>to</span> <span m=''616380''>do</span>
  <span m=''617040''>with</span> <span m=''617230''>that,</span> <span m=''619300''>and</span>
  <span m=''619540''>it''s</span> <span m=''619670''>a</span> <span m=''619740''>pretty</span>
  <span m=''620020''>fundamental</span> <span m=''620540''>problem.</span> <span m=''621100''>Actually,</span>
  <span m=''621430''>we''re</span> <span m=''621790''>talking</span> <span m=''622200''>there</span>
  <span m=''622380''>about</span> <span m=''622640''>what</span> <span m=''624400''>MATLAB''s</span>
  <span m=''624960''>backslash</span> <span m=''625690''>operation</span> <span m=''626930''>will</span>
  <span m=''627180''>do</span> <span m=''627500''>for</span> <span m=''628420''>this</span>
  <span m=''628640''>equation.</span> <span m=''629970''>So</span> <span m=''630090''>MATLAB''S</span>
  <span m=''630620''>backslash</span> <span m=''631260''>operation</span> <span m=''631890''>will</span>
  <span m=''632190''>use</span> <span m=''632410''>elimination;</span> <span m=''633100''>it</span>
  <span m=''633240''>won''t</span> <span m=''633530''>use</span> <span m=''634150''>fast</span>
  <span m=''634520''>Poisson</span> <span m=''635190''>solvers,</span> <span m=''635470''>but</span>
  <span m=''635640''>now</span> <span m=''635880''>let</span> <span m=''636060''>me</span>
  <span m=''636230''>come</span> <span m=''636520''>to</span> <span m=''636650''>the</span>
  <span m=''636790''>fast</span> <span m=''637390''>Poisson</span> <span m=''637710''>solver.</span>
  <span m=''638760''>OK.</span> </p><p><span m=''639870''>So</span> <span m=''641300''>I</span>
  <span m=''641390''>guess</span> <span m=''641710''>the</span> <span m=''641800''>main</span>
  <span m=''642090''>point</span> <span m=''642370''>is</span> <span m=''642500''>I</span>
  <span m=''642620''>have</span> <span m=''642800''>to</span> <span m=''642940''>say</span>
  <span m=''643200''>what</span> <span m=''643740''>are</span> <span m=''643960''>the</span>
  <span m=''644100''>eigenvalues</span> <span m=''644730''>and</span> <span m=''644880''>eigenvectors,</span>
  <span m=''645910''>and</span> <span m=''646090''>how</span> <span m=''646280''>do</span>
  <span m=''646380''>they</span> <span m=''646500''>get</span> <span m=''646720''>used.</span>
  <span m=''647270''>So</span> <span m=''647570''>let</span> <span m=''647680''>me</span>
  <span m=''647820''>say,</span> <span m=''648060''>how</span> <span m=''648250''>do</span>
  <span m=''648340''>they</span> <span m=''648490''>get</span> <span m=''648670''>used.</span>
  <span m=''649250''>So</span> <span m=''649800''>how</span> <span m=''650260''>can</span>
  <span m=''650420''>I</span> <span m=''650510''>use</span> <span m=''650850''>eigenvalues</span>
  <span m=''651670''>and</span> <span m=''651820''>eigenvectors</span> <span m=''652390''>to</span>
  <span m=''653060''>solve</span> <span m=''653370''>a</span> <span m=''653460''>problem</span>
  <span m=''653820''>like</span> <span m=''654040''>that.</span> <span m=''655870''>Let</span>
  <span m=''656060''>me</span> <span m=''656170''>just</span> <span m=''656410''>call</span>
  <span m=''656630''>it</span> <span m=''656770''>k</span> <span m=''657090''>rather</span>
  <span m=''657440''>than</span> <span m=''657640''>k2d,</span> <span m=''658080''>sorry.</span>
  <span m=''658860''>ku</span> <span m=''659470''>equals f,</span> <span m=''661990''>OK,</span>
  <span m=''664970''>by</span> <span m=''666560''>eigenvectors.</span> <span m=''669780''>OK,</span>
  <span m=''670720''>there are</span> <span m=''670930''>three</span> <span m=''671170''>steps.</span>
  <span m=''672100''>Step</span> <span m=''672550''>one.</span> <span m=''675400''>Expand</span>
  <span m=''676110''>the</span> <span m=''676180''>right-hand</span> <span m=''676700''>side</span>
  <span m=''678870''>as</span> <span m=''679740''>a</span> <span m=''679900''>combination</span>
  <span m=''680530''>of</span> <span m=''680600''>the</span> <span m=''680710''>eigenvectors.</span>
  <span m=''682070''>OK.</span> <span m=''682850''>So</span> <span m=''682960''>expand</span>
  <span m=''685500''>f,</span> <span m=''686880''>this</span> <span m=''687250''>right-hand</span>
  <span m=''687750''>side</span> <span m=''688090''>vector,</span> <span m=''688840''>as</span>
  <span m=''689010''>some</span> <span m=''689360''>combination</span> <span m=''691110''>of</span>
  <span m=''692030''>the</span> <span m=''692190''>first</span> <span m=''692570''>eigenvector,</span>
  <span m=''694250''>maybe</span> <span m=''694600''>I''m</span> <span m=''694810''>going
  to</span> <span m=''695060''>call</span> <span m=''695440''>it</span> <span m=''695680''>y1.</span>
  <span m=''697840''>Second</span> <span m=''698480''>eigenvector,</span> <span m=''701570''>nth</span>
  <span m=''701970''>eigenvector,</span> <span m=''704830''>OK,</span> <span m=''706630''>good.</span>
  <span m=''708440''>That</span> <span m=''708600''>means</span> <span m=''708950''>what</span>
  <span m=''709120''>do</span> <span m=''709190''>I</span> <span m=''709300''>mean,</span>
  <span m=''709620''>I</span> <span m=''709720''>mean</span> <span m=''709970''>you</span>
  <span m=''710070''>have</span> <span m=''710230''>to</span> <span m=''710380''>find</span>
  <span m=''710740''>those</span> <span m=''711010''>c''s,</span> <span m=''711840''>that''s</span>
  <span m=''712170''>the</span> <span m=''712320''>job there.</span> <span m=''714000''>Find</span>
  <span m=''714360''>the</span> <span m=''716080''>co-efficients.</span> <span m=''718170''>So</span>
  <span m=''718310''>that''s</span> <span m=''720640''>a</span> <span m=''720770''>job,</span>
  <span m=''721220''>a</span> <span m=''721350''>numerical --</span> <span m=''722430''>it''s</span>
  <span m=''722600''>a</span> <span m=''722680''>linear</span> <span m=''723050''>system</span>
  <span m=''723460''>to</span> <span m=''723570''>solve and</span> <span m=''723990''>we''ll</span>
  <span m=''724160''>see</span> <span m=''724370''>what</span> <span m=''724560''>it</span>
  <span m=''724690''>amounts to.</span> <span m=''725860''>OK,</span> <span m=''726200''>but</span>
  <span m=''726400''>suppose</span> <span m=''727430''>the</span> <span m=''727550''>right-hand</span>
  <span m=''727970''>side</span> <span m=''728230''>is</span> <span m=''728290''>a</span>
  <span m=''728370''>combination</span> <span m=''728960''>of</span> <span m=''729030''>the</span>
  <span m=''729130''>eigenvectors,</span> <span m=''730300''>how</span> <span m=''730500''>can</span>
  <span m=''730670''>you</span> <span m=''730760''>use</span> <span m=''731080''>that?</span>
  <span m=''731600''>Well,</span> <span m=''731830''>step two</span> <span m=''732190''>is</span>
  <span m=''732510''>the</span> <span m=''732610''>real</span> <span m=''732840''>quick</span>
  <span m=''733110''>step.</span> <span m=''734320''>Divide</span> <span m=''738770''>each</span>
  <span m=''740190''>ci</span> <span m=''743690''>by</span> <span m=''743980''>the</span>
  <span m=''744050''>eigenvector,</span> <span m=''745610''>eigenvalue,</span> <span
  m=''748300''>lambda.</span> <span m=''750910''>OK,</span> <span m=''751220''>so</span>
  <span m=''751340''>it''s</span> <span m=''751540''>my</span> <span m=''751790''>eigenvector,</span>
  <span m=''752490''>so</span> <span m=''752610''>I''m</span> <span m=''752820''>assuming</span>
  <span m=''753340''>that</span> <span m=''753540''>kyi</span> <span m=''756250''>is</span>
  <span m=''756580''>lambda</span> <span m=''757390''>iyi</span> <span m=''758440''>and</span>
  <span m=''758670''>that</span> <span m=''758780''>we</span> <span m=''758950''>know</span>
  <span m=''759270''>these</span> <span m=''759590''>guys.</span> <span m=''761890''>So</span>
  <span m=''762110''>this</span> <span m=''762680''>is</span> <span m=''762840''>known.</span>
  <span m=''764670''>And</span> <span m=''764870''>now</span> <span m=''765060''>the</span>
  <span m=''765210''>question,</span> <span m=''765820''>I''m</span> <span m=''766020''>just</span>
  <span m=''766300''>saying,</span> <span m=''766660''>how</span> <span m=''766880''>do</span>
  <span m=''766970''>we</span> <span m=''768010''>assume</span> <span m=''768490''>known?</span>
  </p><p><span m=''773340''>So</span> <span m=''773460''>my</span> <span m=''773570''>question</span>
  <span m=''774000''>now</span> <span m=''774210''>is</span> <span m=''774310''>how</span>
  <span m=''774480''>do</span> <span m=''774570''>we use it?</span> <span m=''775250''>OK,</span>
  <span m=''775580''>step</span> <span m=''775900''>one,</span> <span m=''777840''>the</span>
  <span m=''777960''>idea</span> <span m=''778230''>is</span> <span m=''778350''>going
  to</span> <span m=''778540''>be</span> <span m=''778700''>write</span> <span m=''779120''>everything</span>
  <span m=''779540''>in</span> <span m=''779660''>terms</span> <span m=''779980''>of</span>
  <span m=''780120''>eigenvectors.</span> <span m=''781850''>Work</span> <span m=''782140''>with</span>
  <span m=''782280''>the</span> <span m=''782360''>eigenvectors,</span> <span m=''783160''>because</span>
  <span m=''784170''>if</span> <span m=''784320''>I''ve</span> <span m=''784490''>got</span>
  <span m=''784680''>eigenvectors,</span> <span m=''786060''>the</span> <span m=''786670''>step</span>
  <span m=''788340''>is</span> <span m=''789040''>scaler;</span> <span m=''789990''>I</span>
  <span m=''790110''>just</span> <span m=''790340''>divide</span> <span m=''790840''>these</span>
  <span m=''791110''>numbers</span> <span m=''791590''>by</span> <span m=''791790''>those</span>
  <span m=''792060''>numbers,</span> <span m=''792610''>and</span> <span m=''792800''>then</span>
  <span m=''793180''>I''ve</span> <span m=''793350''>got</span> <span m=''793530''>the</span>
  <span m=''793630''>answer.</span> <span m=''795370''>And</span> <span m=''795590''>then</span>
  <span m=''795980''>construct,</span> <span m=''798110''>the</span> <span m=''798520''>correct</span>
  <span m=''798930''>answer</span> <span m=''799310''>will</span> <span m=''799560''>be</span>
  <span m=''799820''>u,</span> <span m=''801030''>will</span> <span m=''801230''>be</span>
  <span m=''801860''>c1</span> <span m=''803140''>over</span> <span m=''803240''>lambda</span>
  <span m=''803700''>1y1</span> <span m=''806350''>and</span> <span m=''807040''>c2</span>
  <span m=''807870''>over</span> <span m=''808250''>lambda</span> <span m=''808710''>2y2</span>
  <span m=''810200''>up</span> <span m=''810460''>to</span> <span m=''811750''>cn</span>
  <span m=''812680''>over</span> <span m=''813460''>lambda</span> <span m=''814050''>nyn,</span>
  <span m=''817450''>a</span> <span m=''817590''>combination</span> <span m=''818330''>of</span>
  <span m=''818430''>those</span> <span m=''818680''>same</span> <span m=''818980''>eigenvectors</span>
  <span m=''820930''>with</span> <span m=''821120''>the</span> <span m=''821250''>same</span>
  <span m=''821550''>coefficients,</span> <span m=''822320''>just</span> <span m=''822610''>divided</span>
  <span m=''823100''>by</span> <span m=''823260''>lambda.</span> <span m=''827310''>But</span>
  <span m=''827550''>this</span> <span m=''827800''>is,</span> <span m=''828450''>of</span>
  <span m=''828670''>course,</span> <span m=''829110''>another</span> <span m=''829810''>numerical</span>
  <span m=''830370''>job;</span> <span m=''830790''>this</span> <span m=''831030''>is</span>
  <span m=''831840''>like</span> <span m=''832140''>adding</span> <span m=''832540''>up</span>
  <span m=''832680''>a Fourier</span> <span m=''833270''>series;</span> <span m=''834540''>this</span>
  <span m=''834750''>is</span> <span m=''834920''>like</span> <span m=''835150''>finding</span>
  <span m=''835590''>the</span> <span m=''835700''>Fourier</span> <span m=''836070''>coefficients,</span>
  <span m=''836650''>this</span> <span m=''836860''>is</span> <span m=''837010''>like</span>
  <span m=''837660''>reconstructing</span> <span m=''838610''>the</span> <span m=''839790''>input,</span>
  <span m=''840980''>only</span> <span m=''842090''>because</span> <span m=''842450''>I''ve</span>
  <span m=''842610''>divided</span> <span m=''843050''>by</span> <span m=''843200''>lamba</span>
  <span m=''843620''>i,</span> <span m=''844150''>I''m getting</span> <span m=''844910''>the</span>
  <span m=''845040''>output</span> <span m=''845660''>here</span> <span m=''846020''>is</span>
  <span m=''846250''>u,</span> <span m=''847080''>when</span> <span m=''847310''>the</span>
  <span m=''847430''>input</span> <span m=''847880''>was</span> <span m=''848110''>x.</span>
  <span m=''849430''>And</span> <span m=''849740''>do</span> <span m=''849810''>you</span>
  <span m=''849940''>see</span> <span m=''850150''>that</span> <span m=''850300''>that</span>
  <span m=''850700''>is</span> <span m=''850890''>the</span> <span m=''851010''>correct</span>
  <span m=''851410''>answer?</span> <span m=''853690''>All</span> <span m=''853900''>I</span>
  <span m=''853990''>have</span> <span m=''854150''>to</span> <span m=''854270''>do</span>
  <span m=''854400''>is</span> <span m=''854580''>check</span> <span m=''854970''>that
  ku</span> <span m=''855720''>equals</span> <span m=''856120''>f,</span> <span m=''856840''>so</span>
  <span m=''857010''>check</span> <span m=''860480''>that</span> <span m=''860740''>this</span>
  <span m=''862870''>answer</span> <span m=''863360''>from</span> <span m=''863630''>step</span>
  <span m=''863920''>three</span> <span m=''864170''>is</span> <span m=''864700''>the</span>
  <span m=''864810''>right</span> <span m=''865050''>answer.</span> <span m=''866040''>OK,</span>
  <span m=''866700''>so</span> <span m=''866860''>I</span> <span m=''866940''>multiplied</span>
  <span m=''867490''>by</span> <span m=''867660''>k.</span> <span m=''869340''>When</span>
  <span m=''869510''>I</span> <span m=''869690''>multiply</span> <span m=''871670''>y1</span>
  <span m=''872290''>by</span> <span m=''872520''>k,</span> <span m=''874960''>a</span>
  <span m=''875070''>factor</span> <span m=''875460''>lambda</span> <span m=''875850''>1</span>
  <span m=''876400''>appears,</span> <span m=''877530''>the</span> <span m=''877690''>eigenvalue;</span>
  <span m=''878680''>it</span> <span m=''878850''>cancels</span> <span m=''879340''>that;</span>
  <span m=''879850''>well</span> <span m=''880040''>that''s</span> <span m=''880280''>y</span>
  <span m=''880590''>divided,</span> <span m=''881140''>so</span> <span m=''881340''>it</span>
  <span m=''881470''>would</span> <span m=''881640''>cancel,</span> <span m=''882480''>and</span>
  <span m=''882690''>I</span> <span m=''882790''>have</span> <span m=''883130''>c1y1.</span>
  <span m=''884640''>When</span> <span m=''884820''>I</span> <span m=''884970''>multiply</span>
  <span m=''885300''>this</span> <span m=''885590''>by</span> <span m=''885790''>k,</span>
  <span m=''886730''>ky2</span> <span m=''888210''>is</span> <span m=''888460''>lambda</span>
  <span m=''888750''>2y2;</span> <span m=''889940''>cancel</span> <span m=''890420''>the</span>
  <span m=''890670''>lambda</span> <span m=''890780''>2s,</span> <span m=''891280''>and</span>
  <span m=''891430''>you''re</span> <span m=''891550''>left</span> <span m=''891890''>with</span>
  <span m=''892340''>c2y2,</span> <span m=''894250''>and</span> <span m=''894550''>so</span>
  <span m=''894690''>on.</span> <span m=''895000''>So,</span> <span m=''896140''>when</span>
  <span m=''896310''>I</span> <span m=''896370''>multiplied</span> <span m=''896640''>by</span>
  <span m=''897030''>k,</span> <span m=''898200''>I</span> <span m=''898330''>got</span>
  <span m=''899770''>f.</span> <span m=''901570''>That''s</span> <span m=''901780''>it.</span>
  </p><p><span m=''902250''>So</span> <span m=''902460''>that''s</span> <span m=''902730''>the</span>
  <span m=''902840''>whole</span> <span m=''903120''>idea,</span> <span m=''906040''>written</span>
  <span m=''906270''>out,</span> <span m=''907430''>but</span> <span m=''907620''>now</span>
  <span m=''909760''>what</span> <span m=''910410''>actual</span> <span m=''911020''>computations</span>
  <span m=''912010''>go</span> <span m=''912210''>into</span> <span m=''912590''>steps</span>
  <span m=''913010''>one and</span> <span m=''913720''>three?</span> <span m=''914430''>Step</span>
  <span m=''914740''>two</span> <span m=''914950''>is</span> <span m=''915120''>pretty</span>
  <span m=''915380''>simple.</span> <span m=''915840''>Well,</span> <span m=''916250''>actually</span>
  <span m=''916920''>this</span> <span m=''917170''>is</span> <span m=''917350''>a</span>
  <span m=''917450''>good</span> <span m=''917660''>way</span> <span m=''917860''>to</span>
  <span m=''918290''>look</span> <span m=''918660''>it.</span> <span m=''919740''>I</span>
  <span m=''920060''>want to</span> <span m=''920270''>write</span> <span m=''920510''>that</span>
  <span m=''920720''>same</span> <span m=''921030''>algorithm</span> <span m=''921660''>in</span>
  <span m=''921870''>matrix</span> <span m=''922600''>language.</span> <span m=''923790''>OK,</span>
  <span m=''924580''>so</span> <span m=''925740''>in</span> <span m=''925940''>matrix</span>
  <span m=''926470''>form</span> <span m=''929790''>we have</span> <span m=''930340''>the</span>
  <span m=''930420''>matrix</span> <span m=''930930''>of</span> <span m=''931050''>eigenvectors,</span>
  <span m=''931850''>and</span> <span m=''934700''>that''s</span> <span m=''935110''>what</span>
  <span m=''935320''>I''m</span> <span m=''935460''>calling</span> <span m=''935830''>s.</span>
  <span m=''936910''>And</span> <span m=''937170''>it''s</span> <span m=''937320''>got</span>
  <span m=''937540''>the</span> <span m=''937680''>eigenvectors</span> <span m=''938580''>y1</span>
  <span m=''939450''>y2,</span> <span m=''940850''>yn,</span> <span m=''941300''>and</span>
  <span m=''941640''>it''s columns,</span> <span m=''943320''>and</span> <span m=''943570''>the</span>
  <span m=''943650''>eigenvalue</span> <span m=''944620''>matrix,</span> <span m=''950280''>we</span>
  <span m=''950450''>need</span> <span m=''950720''>a</span> <span m=''951100''>name</span>
  <span m=''951450''>for</span> <span m=''951580''>that</span> <span m=''951840''>too,</span>
  <span m=''952090''>and</span> <span m=''952240''>that</span> <span m=''952790''>we</span>
  <span m=''952960''>decided</span> <span m=''953300''>to</span> <span m=''953370''>call</span>
  <span m=''953690''>lambda,</span> <span m=''954860''>and</span> <span m=''955080''>that''s</span>
  <span m=''955390''>got</span> <span m=''956150''>the</span> <span m=''956300''>eigenvalues</span>
  <span m=''957770''>on</span> <span m=''958100''>its</span> <span m=''958490''>diagonal.</span>
  <span m=''961480''>So</span> <span m=''963650''>this</span> <span m=''963890''>is</span>
  <span m=''965410''>18.06</span> <span m=''966170''>linear</span> <span m=''966490''>algebra.</span>
  <span m=''968030''>The</span> <span m=''970120''>matrix</span> <span m=''970620''>of</span>
  <span m=''970720''>eigenvectors</span> <span m=''971320''>if</span> <span m=''971460''>I</span>
  <span m=''971820''>multiply</span> <span m=''972370''>k</span> <span m=''973080''>by</span>
  <span m=''973370''>s,</span> <span m=''976020''>then</span> <span m=''976500''>I''m</span>
  <span m=''976700''>multiplying</span> <span m=''977410''>k</span> <span m=''977960''>by</span>
  <span m=''978260''>all</span> <span m=''978630''>its</span> <span m=''978980''>little</span>
  <span m=''979320''>eigenvectors,</span> <span m=''981770''>and</span> <span m=''982100''>k</span>
  <span m=''982420''>times</span> <span m=''982810''>this</span> <span m=''983340''>gives</span>
  <span m=''983700''>me</span> <span m=''984510''>lambda</span> <span m=''985050''>1y1,</span>
  <span m=''986280''>k</span> <span m=''986670''>times</span> <span m=''987050''>y2</span>
  <span m=''987670''>gives</span> <span m=''987890''>me</span> <span m=''988050''>lambda</span>
  <span m=''988320''>2y2,</span> <span m=''989250''>kyn</span> <span m=''990450''>is</span>
  <span m=''990890''>lambda</span> <span m=''991310''>nyn,</span> <span m=''995620''>and</span>
  <span m=''996180''>if</span> <span m=''996360''>I</span> <span m=''996540''>look</span>
  <span m=''996800''>to</span> <span m=''996920''>see</span> <span m=''997120''>what</span>
  <span m=''997390''>this</span> <span m=''997630''>is,</span> <span m=''998250''>this</span>
  <span m=''998500''>is</span> <span m=''998650''>the</span> <span m=''998790''>same</span>
  <span m=''999180''>as</span> <span m=''999590''>y1</span> <span m=''1000440''>to</span>
  <span m=''1000700''>yn</span> <span m=''1001670''>multiplied</span> <span m=''1002400''>by</span>
  <span m=''1002580''>lambda.</span> <span m=''1004060''>If</span> <span m=''1004220''>I</span>
  <span m=''1004320''>just</span> <span m=''1005220''>multiply</span> <span m=''1005470''>[UNINTELLIGIBLE]</span>
  <span m=''1005750''>on</span> <span m=''1005930''>the</span> <span m=''1006010''>right</span>
  <span m=''1006350''>by</span> <span m=''1006500''>lambda,</span> <span m=''1007070''>it
  will</span> <span m=''1007390''>take</span> <span m=''1007690''>lambda</span> <span
  m=''1008090''>1</span> <span m=''1008350''>times</span> <span m=''1008670''>the</span>
  <span m=''1008770''>first</span> <span m=''1009060''>column,</span> <span m=''1009420''>lamda</span>
  <span m=''1010250''>2</span> <span m=''1010490''>times</span> <span m=''1010820''>the</span>
  <span m=''1010910''>second</span> <span m=''1011250''>lambda</span> <span m=''1011470''>n</span>
  <span m=''1011750''>times</span> <span m=''1012030''>the</span> <span m=''1012090''>third,</span>
  <span m=''1012380''>which</span> <span m=''1012610''>is,</span> <span m=''1012760''>times</span>
  <span m=''1013160''>the</span> <span m=''1013250''>last,</span> <span m=''1013650''>which</span>
  <span m=''1013850''>is</span> <span m=''1013970''>what</span> <span m=''1014150''>we</span>
  <span m=''1014260''>want,</span> <span m=''1014770''>so</span> <span m=''1015020''>it''s</span>
  <span m=''1015170''>s</span> <span m=''1015440''>lambda.</span> <span m=''1018660''>This</span>
  <span m=''1018940''>is</span> <span m=''1019980''>all</span> <span m=''1020560''>n</span>
  <span m=''1020990''>eigenvalues</span> <span m=''1021880''>and</span> <span m=''1022040''>eigenvectors</span>
  <span m=''1022830''>in</span> <span m=''1023040''>one</span> <span m=''1023920''>matrix</span>
  <span m=''1024810''>equation,</span> <span m=''1025580''>that''s</span> <span m=''1025840''>all</span>
  <span m=''1026050''>that</span> <span m=''1026270''>is.</span> <span m=''1027330''>It''s</span>
  <span m=''1027820''>just</span> <span m=''1028580''>ks</span> <span m=''1029290''>equal</span>
  <span m=''1029690''>s</span> <span m=''1029960''>lambda</span> <span m=''1030700''>i</span>
  <span m=''1030920''>just</span> <span m=''1031370''>says,</span> <span m=''1033130''>this</span>
  <span m=''1036720''>for</span> <span m=''1037030''>all</span> <span m=''1037540''>i</span>
  <span m=''1037790''>at</span> <span m=''1037990''>once,</span> <span m=''1038710''>all</span>
  <span m=''1038960''>i</span> <span m=''1039120''>at</span> <span m=''1039260''>the</span>
  <span m=''1039410''>same</span> <span m=''1039700''>time.</span> <span m=''1040470''>OK.</span>
  </p><p><span m=''1041320''>So</span> <span m=''1041780''>if</span> <span m=''1042010''>I</span>
  <span m=''1042160''>use</span> <span m=''1042600''>these</span> <span m=''1042870''>matrices</span>
  <span m=''1044750''>in</span> <span m=''1045170''>describing</span> <span m=''1046000''>steps</span>
  <span m=''1046470''>one,</span> <span m=''1046790''>two,</span> <span m=''1047030''>three,</span>
  <span m=''1048150''>I''ll</span> <span m=''1048600''>see</span> <span m=''1048830''>what''s</span>
  <span m=''1049040''>happening</span> <span m=''1050030''>matrix</span> <span m=''1050530''>language.</span>
  <span m=''1052740''>OK,</span> <span m=''1053670''>let</span> <span m=''1053810''>me</span>
  <span m=''1053920''>just</span> <span m=''1054150''>do</span> <span m=''1054280''>that.</span>
  <span m=''1054770''>Step</span> <span m=''1055080''>one,</span> <span m=''1058400''>step</span>
  <span m=''1058680''>one</span> <span m=''1059930''>is</span> <span m=''1060210''>looking</span>
  <span m=''1060670''>for</span> <span m=''1060890''>f</span> <span m=''1061550''>as</span>
  <span m=''1061790''>a</span> <span m=''1061900''>combination</span> <span m=''1062890''>of</span>
  <span m=''1063070''>the</span> <span m=''1063200''>columns</span> <span m=''1064090''>of</span>
  <span m=''1064880''>s.</span> <span m=''1066230''>So</span> <span m=''1066400''>step</span>
  <span m=''1066800''>one</span> <span m=''1067220''>is</span> <span m=''1067480''>just</span>
  <span m=''1067850''>f</span> <span m=''1068420''>equals</span> <span m=''1069100''>s</span>
  <span m=''1069970''>times</span> <span m=''1070370''>c.</span> <span m=''1072220''>The</span>
  <span m=''1072390''>vector</span> <span m=''1072740''>of</span> <span m=''1074630''>coefficients</span>
  <span m=''1076230''>multiplies</span> <span m=''1077270''>the</span> <span m=''1078270''>columns</span>
  <span m=''1078830''>of</span> <span m=''1078980''>s</span> <span m=''1080110''>and</span>
  <span m=''1080370''>adds</span> <span m=''1081060''>to</span> <span m=''1081220''>give</span>
  <span m=''1082500''>f.</span> <span m=''1084080''>Then</span> <span m=''1084290''>step</span>
  <span m=''1084560''>two,</span> <span m=''1087700''>which</span> <span m=''1088060''>just</span>
  <span m=''1089030''>divides</span> <span m=''1090880''>everything</span> <span m=''1091540''>by
  --</span> <span m=''1093870''>divides</span> <span m=''1094480''>by</span> <span
  m=''1094770''>the</span> <span m=''1094910''>lambdas.</span> <span m=''1095310''>Step</span>
  <span m=''1096230''>two</span> <span m=''1096720''>just</span> <span m=''1097010''>creates</span>
  <span m=''1097920''>lambda</span> <span m=''1098360''>inverse,</span> <span m=''1100310''>sc.</span>
  <span m=''1102850''>So</span> <span m=''1103330''>I</span> <span m=''1103450''>took</span>
  <span m=''1104900''>what</span> <span m=''1105100''>I</span> <span m=''1105170''>had
  --</span> <span m=''1107180''>let''s</span> <span m=''1107570''>see,</span> <span
  m=''1108350''>no,</span> <span m=''1110880''>the</span> <span m=''1111080''>lambda</span>
  <span m=''1111430''>inverse</span> <span m=''1111810''>better</span> <span m=''1112040''>be</span>
  <span m=''1112220''>multiplying</span> <span m=''1113000''>the</span> <span m=''1113180''>c.</span>
  <span m=''1114500''>Well,</span> <span m=''1114760''>actually</span> <span m=''1115730''>I</span>
  <span m=''1115890''>can</span> <span m=''1115970''>do it</span> <span m=''1116210''>all</span>
  <span m=''1116470''>in --</span> <span m=''1117250''>well</span> <span m=''1118420''>step</span>
  <span m=''1118660''>two,</span> <span m=''1121150''>that''s</span> <span m=''1121370''>the</span>
  <span m=''1121440''>easiest</span> <span m=''1121910''>step,</span> <span m=''1122290''>I</span>
  <span m=''1122340''>should</span> <span m=''1122620''>be</span> <span m=''1122760''>able</span>
  <span m=''1122980''>to</span> <span m=''1123100''>do</span> <span m=''1123240''>it.</span>
  <span m=''1123930''>c</span> <span m=''1124610''>is</span> <span m=''1124870''>changed</span>
  <span m=''1125440''>to</span> <span m=''1128470''>lambda</span> <span m=''1128880''>inverse</span>
  <span m=''1129440''>c,</span> <span m=''1132150''>so</span> <span m=''1132340''>that</span>
  <span m=''1132660''>c</span> <span m=''1132980''>becomes</span> <span m=''1133440''>lambda</span>
  <span m=''1133760''>inverse</span> <span m=''1134400''>c,</span> <span m=''1135280''>OK.</span>
  <span m=''1136030''>And</span> <span m=''1136200''>then</span> <span m=''1136390''>step</span>
  <span m=''1136730''>three</span> <span m=''1137770''>uses</span> <span m=''1139220''>lambda</span>
  <span m=''1139540''>inverse</span> <span m=''1140050''>c</span> <span m=''1141600''>to</span>
  <span m=''1142560''>construct</span> <span m=''1145250''>u.</span> <span m=''1146460''>So</span>
  <span m=''1147130''>step</span> <span m=''1148270''>three</span> <span m=''1149760''>is</span>
  <span m=''1150600''>the</span> <span m=''1150750''>answer</span> <span m=''1151190''>u,</span>
  <span m=''1152380''>what</span> <span m=''1153040''>do</span> <span m=''1153110''>I</span>
  <span m=''1153230''>have</span> <span m=''1153510''>here?</span> <span m=''1154540''>I''ve</span>
  <span m=''1154790''>got</span> <span m=''1155010''>a</span> <span m=''1155090''>combination</span>
  <span m=''1155850''>of</span> <span m=''1155940''>these</span> <span m=''1156080''>vectors,</span>
  <span m=''1156740''>so</span> <span m=''1156920''>they''re</span> <span m=''1157180''>the</span>
  <span m=''1157330''>columns</span> <span m=''1157870''>of s,</span> <span m=''1159030''>and</span>
  <span m=''1159270''>what</span> <span m=''1159500''>are</span> <span m=''1159570''>they</span>
  <span m=''1159690''>multiplied</span> <span m=''1160230''>by?</span> <span m=''1160580''>They''re</span>
  <span m=''1160760''>multiplied</span> <span m=''1161130''>by</span> <span m=''1161440''>the</span>
  <span m=''1161560''>c''s</span> <span m=''1162070''>over</span> <span m=''1162330''>lambdas,</span>
  <span m=''1162980''>which</span> <span m=''1163220''>is</span> <span m=''1163430''>what</span>
  <span m=''1163660''>I</span> <span m=''1163770''>have</span> <span m=''1164010''>here.</span>
  <span m=''1164610''>That''s</span> <span m=''1164960''>s</span> <span m=''1165680''>lambda</span>
  <span m=''1166160''>inverse</span> <span m=''1167030''>c.</span> <span m=''1173650''>Those</span>
  <span m=''1173890''>are</span> <span m=''1173980''>the</span> <span m=''1174100''>three</span>
  <span m=''1174350''>steps.</span> </p><p><span m=''1176840''>And</span> <span m=''1180880''>what''s</span>
  <span m=''1181200''>the</span> <span m=''1181300''>work</span> <span m=''1181630''>involved?</span>
  <span m=''1182900''>Here,</span> <span m=''1183190''>the</span> <span m=''1183320''>work</span>
  <span m=''1183690''>is</span> <span m=''1184090''>solving</span> <span m=''1184330''>a</span>
  <span m=''1184580''>linear</span> <span m=''1184930''>system</span> <span m=''1186130''>with</span>
  <span m=''1186830''>the</span> <span m=''1186960''>matrix</span> <span m=''1187410''>s.</span>
  <span m=''1189910''>Here,</span> <span m=''1190530''>the</span> <span m=''1190660''>work</span>
  <span m=''1191070''>is</span> <span m=''1192070''>taking</span> <span m=''1192840''>a</span>
  <span m=''1192970''>combination</span> <span m=''1193670''>of</span> <span m=''1193770''>the</span>
  <span m=''1193860''>columns</span> <span m=''1194310''>of</span> <span m=''1194600''>s,</span>
  <span m=''1195710''>doing</span> <span m=''1195960''>a</span> <span m=''1196010''>matrix</span>
  <span m=''1196460''>multiplication.</span> <span m=''1199650''>Those</span> <span
  m=''1200360''>two</span> <span m=''1201030''>steps</span> <span m=''1201440''>are</span>
  <span m=''1201610''>usually</span> <span m=''1204170''>full-scale</span> <span m=''1205020''>matrix</span>
  <span m=''1205490''>operation,</span> <span m=''1206820''>and</span> <span m=''1207210''>of</span>
  <span m=''1207300''>course,</span> <span m=''1207630''>the</span> <span m=''1207750''>s
  ,</span> <span m=''1208830''>if</span> <span m=''1209130''>I</span> <span m=''1209240''>just</span>
  <span m=''1209510''>complete</span> <span m=''1209970''>this,</span> <span m=''1210610''>I''ll</span>
  <span m=''1210790''>see</span> <span m=''1211070''>that</span> <span m=''1211330''>I</span>
  <span m=''1211410''>get</span> <span m=''1211630''>the</span> <span m=''1211750''>right</span>
  <span m=''1212030''>thing</span> <span m=''1212220''>that''s</span> <span m=''1212360''>s</span>
  <span m=''1213340''>lambda</span> <span m=''1213770''>inverse</span> <span m=''1215880''>and</span>
  <span m=''1216730''>c</span> <span m=''1217390''>is</span> <span m=''1217960''>s</span>
  <span m=''1218180''>inverse</span> <span m=''1218670''>s.</span> <span m=''1222910''>There''s</span>
  <span m=''1223250''>the</span> <span m=''1223390''>answer.</span> <span m=''1224360''>u</span>
  <span m=''1225510''>is</span> <span m=''1226030''>s</span> <span m=''1227230''>lambda</span>
  <span m=''1227940''>inverse,</span> <span m=''1228770''>that''s a</span> <span m=''1228890''>lambda</span>
  <span m=''1229320''>inverse</span> <span m=''1229930''>there:</span> <span m=''1231200''>s</span>
  <span m=''1231480''>inverse</span> <span m=''1231850''>f.</span> <span m=''1232890''>That''s</span>
  <span m=''1233540''>the</span> <span m=''1233660''>correct</span> <span m=''1234050''>answer</span>
  <span m=''1234950''>in</span> <span m=''1235170''>matrix</span> <span m=''1235990''>language.</span>
  <span m=''1237190''>Right.</span> <span m=''1240390''>This</span> <span m=''1240640''>is</span>
  <span m=''1240860''>k</span> <span m=''1241130''>inverse,</span> <span m=''1242170''>that''s</span>
  <span m=''1242460''>k</span> <span m=''1242700''>inverse.</span> <span m=''1243850''>k</span>
  <span m=''1244350''>is</span> <span m=''1247740''>s</span> <span m=''1248950''>lamda</span>
  <span m=''1249880''>s</span> <span m=''1251920''>inverse, and</span> <span m=''1252570''>if</span>
  <span m=''1252730''>I</span> <span m=''1252930''>take</span> <span m=''1253190''>the</span>
  <span m=''1253300''>inverse</span> <span m=''1253700''>of</span> <span m=''1253820''>that,</span>
  <span m=''1254570''>I</span> <span m=''1254690''>get</span> <span m=''1255020''>s</span>
  <span m=''1256360''>lambda</span> <span m=''1256730''>inverse,</span> <span m=''1257800''>s</span>
  <span m=''1258120''>inverse</span> <span m=''1258730''>to</span> <span m=''1258880''>multiply</span>
  <span m=''1259410''>f.</span> <span m=''1260000''>Well,</span> <span m=''1263830''>I</span>
  <span m=''1264560''>doubt</span> <span m=''1264910''>if</span> <span m=''1265020''>you''re</span>
  <span m=''1265180''>much</span> <span m=''1265440''>impressed</span> <span m=''1265990''>by</span>
  <span m=''1266180''>this</span> <span m=''1266480''>lower</span> <span m=''1266820''>board,</span>
  <span m=''1267230''>because</span> <span m=''1267830''>the</span> <span m=''1267960''>upper</span>
  <span m=''1268190''>board</span> <span m=''1269290''>was</span> <span m=''1270550''>the</span>
  <span m=''1270690''>same</span> <span m=''1271000''>thing</span> <span m=''1272960''>written</span>
  <span m=''1273310''>out.</span> <span m=''1273800''>It</span> <span m=''1274080''>took</span>
  <span m=''1277630''>some</span> <span m=''1277840''>indication</span> <span m=''1278570''>of</span>
  <span m=''1278710''>what</span> <span m=''1278990''>the</span> <span m=''1279650''>separate</span>
  <span m=''1280680''>pieces</span> <span m=''1281140''>were,</span> <span m=''1281390''>but</span>
  <span m=''1281690''>it''s</span> <span m=''1282040''>pretty</span> <span m=''1282310''>clear.</span>
  </p><p><span m=''1283420''>OK,</span> <span m=''1284150''>now</span> <span m=''1287730''>the</span>
  <span m=''1288810''>million</span> <span m=''1289180''>dollar</span> <span m=''1289470''>question</span>
  <span m=''1289920''>is,</span> <span m=''1291410''>is</span> <span m=''1291590''>it</span>
  <span m=''1291730''>fast?</span> <span m=''1293910''>And</span> <span m=''1294160''>the</span>
  <span m=''1294240''>answer</span> <span m=''1294600''>is,</span> <span m=''1295230''>almost</span>
  <span m=''1295620''>certainly</span> <span m=''1295980''>no.</span> <span m=''1297930''>But</span>
  <span m=''1298850''>for</span> <span m=''1299100''>the</span> <span m=''1299250''>particular</span>
  <span m=''1299870''>matrix</span> <span m=''1300410''>s,</span> <span m=''1302870''>which</span>
  <span m=''1304880''>by</span> <span m=''1305030''>good</span> <span m=''1305240''>fortune</span>
  <span m=''1305690''>s</span> <span m=''1306060''>could</span> <span m=''1306270''>also</span>
  <span m=''1306620''>stand</span> <span m=''1307090''>for</span> <span m=''1307640''>sine,</span>
  <span m=''1309280''>this</span> <span m=''1309720''>matrix</span> <span m=''1310720''>of</span>
  <span m=''1311840''>eigenvectors</span> <span m=''1313760''>for</span> <span m=''1313920''>this</span>
  <span m=''1314240''>particular</span> <span m=''1314850''>problem</span> <span m=''1315470''>are</span>
  <span m=''1316240''>sines.</span> <span m=''1317130''>These</span> <span m=''1317390''>are</span>
  <span m=''1317500''>the</span> <span m=''1317660''>discrete</span> <span m=''1318160''>sines,</span>
  <span m=''1318490''>so</span> <span m=''1318610''>this</span> <span m=''1318830''>is</span>
  <span m=''1319020''>the</span> <span m=''1319140''>discrete</span> <span m=''1319750''>sine</span>
  <span m=''1320230''>transform.</span> <span m=''1321600''>That''s</span> <span m=''1322360''>we''re</span>
  <span m=''1322490''>doing,</span> <span m=''1322820''>we''re</span> <span m=''1322970''>doing</span>
  <span m=''1323250''>the</span> <span m=''1323360''>discrete</span> <span m=''1323810''>sign</span>
  <span m=''1324140''>transform,</span> <span m=''1325630''>because</span> <span m=''1326070''>those</span>
  <span m=''1326730''>discrete</span> <span m=''1327280''>sine</span> <span m=''1327670''>vectors</span>
  <span m=''1328140''>are</span> <span m=''1328430''>the</span> <span m=''1328600''>eigenvectors</span>
  <span m=''1329560''>of</span> <span m=''1330420''>k.</span> <span m=''1331100''>OK,</span>
  <span m=''1332120''>now</span> <span m=''1333200''>let</span> <span m=''1333400''>me</span>
  <span m=''1336190''>say</span> <span m=''1336420''>what</span> <span m=''1336670''>that</span>
  <span m=''1336880''>means.</span> <span m=''1337590''>First</span> <span m=''1337890''>I''m</span>
  <span m=''1338130''>thinking</span> <span m=''1338480''>of</span> <span m=''1338660''>k</span>
  <span m=''1339770''>in</span> <span m=''1339980''>1d.</span> <span m=''1341180''>So</span>
  <span m=''1341530''>this is</span> <span m=''1341680''>my</span> <span m=''1342010''>2</span>
  <span m=''1343020''>2''s</span> <span m=''1344020''>and</span> <span m=''1344250''>minus</span>
  <span m=''1344640''>1''s</span> <span m=''1345900''>and</span> <span m=''1346120''>minus</span>
  <span m=''1346460''>1.</span> <span m=''1348960''>Its</span> <span m=''1349190''>eigenvectors</span>
  <span m=''1350120''>are</span> <span m=''1350550''>discrete</span> <span m=''1351020''>sines,</span>
  <span m=''1351540''>if</span> <span m=''1351720''>I</span> <span m=''1351850''>multiply</span>
  <span m=''1352390''>that</span> <span m=''1352770''>by</span> <span m=''1353550''>sine</span>
  <span m=''1356940''>kh --</span> <span m=''1358250''>well,</span> <span m=''1358530''>let</span>
  <span m=''1358650''>me</span> <span m=''1358740''>just</span> <span m=''1359050''>take</span>
  <span m=''1359250''>the</span> <span m=''1359360''>first</span> <span m=''1359670''>one,</span>
  <span m=''1360340''>sine</span> <span m=''1360760''>h,</span> <span m=''1361830''>sine</span>
  <span m=''1362170''>2h,</span> <span m=''1364070''>sine</span> <span m=''1366880''>n</span>
  <span m=''1367140''>minus</span> <span m=''1367490''>1h,</span> <span m=''1370080''>that</span>
  <span m=''1370390''>will</span> <span m=''1370580''>turn</span> <span m=''1370870''>out</span>
  <span m=''1371140''>to</span> <span m=''1371290''>be</span> <span m=''1372250''>an</span>
  <span m=''1372530''>eigenvector.</span> <span m=''1376620''>So</span> <span m=''1376810''>this</span>
  <span m=''1377000''>is</span> <span m=''1377200''>ky,</span> <span m=''1379270''>ky1,</span>
  <span m=''1380390''>the</span> <span m=''1380740''>first</span> <span m=''1381160''>eigenvector.</span>
  <span m=''1382630''>The</span> <span m=''1382720''>eigenvectors</span> <span m=''1383460''>are
  --</span> <span m=''1383710''>let</span> <span m=''1383870''>me</span> <span m=''1384010''>draw</span>
  <span m=''1384330''>them.</span> <span m=''1385270''>The</span> <span m=''1385480''>eigenvectors</span>
  <span m=''1387730''>for</span> <span m=''1388570''>that</span> <span m=''1389580''>second</span>
  <span m=''1390000''>difference</span> <span m=''1390380''>matrix</span> <span m=''1390870''>k</span>
  <span m=''1391790''>are --</span> <span m=''1393960''>here''s</span> <span m=''1394300''>the</span>
  <span m=''1394430''>interval,</span> <span m=''1395300''>0 to 1,</span> <span m=''1395760''>I</span>
  <span m=''1395910''>chop</span> <span m=''1396140''>it</span> <span m=''1396360''>up</span>
  <span m=''1396700''>in</span> <span m=''1396850''>steps</span> <span m=''1397270''>of</span>
  <span m=''1397430''>h,</span> <span m=''1398620''>and</span> <span m=''1398890''>I</span>
  <span m=''1399020''>plot</span> <span m=''1401040''>the</span> <span m=''1401260''>sine,</span>
  <span m=''1404930''>which</span> <span m=''1405180''>starts</span> <span m=''1405790''>at</span>
  <span m=''1406000''>zero</span> <span m=''1406270''>and</span> <span m=''1406520''>ends</span>
  <span m=''1406700''>at zero,</span> <span m=''1406900''>because</span> <span m=''1407130''>those</span>
  <span m=''1407420''>are</span> <span m=''1407490''>the</span> <span m=''1407600''>boundary</span>
  <span m=''1408000''>conditions,</span> <span m=''1408960''>and</span> <span m=''1409180''>here
  is</span> <span m=''1409930''>sine</span> <span m=''1410280''>h,</span> <span m=''1410570''>sine</span>
  <span m=''1410920''>2h,</span> <span m=''1411460''>sine</span> <span m=''1411760''>3h,</span>
  <span m=''1412290''>sine</span> <span m=''1412600''>4h,</span> <span m=''1413190''>sine</span>
  <span m=''1413390''>5h,</span> <span m=''1414500''>so</span> <span m=''1414770''>for</span>
  <span m=''1414930''>the</span> <span m=''1415050''>five</span> <span m=''1415430''>by</span>
  <span m=''1415700''>five</span> <span m=''1416180''>case --</span> <span m=''1418250''>maybe</span>
  <span m=''1418550''>I</span> <span m=''1418630''>should</span> <span m=''1418870''>just</span>
  <span m=''1419110''>be</span> <span m=''1419220''>using</span> <span m=''1419570''>n</span>
  <span m=''1419880''>here,</span> <span m=''1422620''>or</span> <span m=''1422770''>maybe</span>
  <span m=''1423030''>I</span> <span m=''1423120''>should</span> <span m=''1423390''>even</span>
  <span m=''1423600''>be</span> <span m=''1423730''>using</span> <span m=''1424140''>capital
  n,</span> <span m=''1425890''>so</span> <span m=''1426430''>capital</span> <span
  m=''1426860''>n</span> <span m=''1427160''>is</span> <span m=''1427470''>5</span>
  <span m=''1427990''>in</span> <span m=''1428090''>this</span> <span m=''1428560''>example.</span>
  <span m=''1433770''>Good.</span> </p><p><span m=''1436250''>What''s</span> <span
  m=''1436940''>on</span> <span m=''1437090''>the</span> <span m=''1437190''>other</span>
  <span m=''1437430''>side</span> <span m=''1437760''>of</span> <span m=''1437850''>that</span>
  <span m=''1438040''>equal</span> <span m=''1438500''>sign?</span> <span m=''1439670''>Some</span>
  <span m=''1440100''>eigenvalue</span> <span m=''1440750''>times</span> <span m=''1441100''>the</span>
  <span m=''1441250''>same</span> <span m=''1441540''>vector,</span> <span m=''1443240''>sine</span>
  <span m=''1443490''>h,</span> <span m=''1445120''>sine</span> <span m=''1445350''>2h,</span>
  <span m=''1446940''>down to</span> <span m=''1447610''>sine</span> <span m=''1448230''>nh,</span>
  <span m=''1450540''>and</span> <span m=''1450830''>that</span> <span m=''1451050''>eigenvalue
  --</span> <span m=''1451620''>oh,</span> <span m=''1451890''>let</span> <span m=''1452020''>me</span>
  <span m=''1452120''>just</span> <span m=''1452400''>write</span> <span m=''1452640''>lambda</span>
  <span m=''1453070''>1</span> <span m=''1453480''>for it.</span> <span m=''1456230''>We</span>
  <span m=''1456410''>know</span> <span m=''1456620''>what</span> <span m=''1456820''>it</span>
  <span m=''1456970''>is.</span> <span m=''1458270''>The</span> <span m=''1458420''>fact</span>
  <span m=''1458750''>that</span> <span m=''1458890''>this</span> <span m=''1459080''>is</span>
  <span m=''1459250''>an</span> <span m=''1459410''>eigenvector</span> <span m=''1461850''>is</span>
  <span m=''1462130''>just</span> <span m=''1463890''>trig;</span> <span m=''1464900''>you</span>
  <span m=''1465020''>know,</span> <span m=''1465210''>I</span> <span m=''1465860''>multiply</span>
  <span m=''1466460''>minus</span> <span m=''1466950''>1</span> <span m=''1467160''>of</span>
  <span m=''1467270''>that</span> <span m=''1467760''>plus</span> <span m=''1468060''>2</span>
  <span m=''1468280''>of</span> <span m=''1468480''>that</span> <span m=''1468860''>minus</span>
  <span m=''1469320''>1</span> <span m=''1469670''>of</span> <span m=''1469790''>sine</span>
  <span m=''1470170''>3h,</span> <span m=''1472060''>and</span> <span m=''1472240''>I</span>
  <span m=''1472310''>use</span> <span m=''1472580''>a</span> <span m=''1472670''>little</span>
  <span m=''1473000''>trig</span> <span m=''1473320''>identity.</span> <span m=''1475050''>So</span>
  <span m=''1475230''>minus</span> <span m=''1475720''>that,</span> <span m=''1476300''>2</span>
  <span m=''1476540''>of</span> <span m=''1476670''>that,</span> <span m=''1477130''>minus</span>
  <span m=''1477570''>that,</span> <span m=''1478280''>turns</span> <span m=''1478600''>out</span>
  <span m=''1478880''>that</span> <span m=''1479100''>to be</span> <span m=''1479750''>a</span>
  <span m=''1479870''>multiple</span> <span m=''1480310''>of</span> <span m=''1480450''>sign</span>
  <span m=''1480760''>2h.</span> <span m=''1481250''>Well</span> <span m=''1482140''>sine</span>
  <span m=''1482580''>2h</span> <span m=''1483110''>give</span> <span m=''1483510''>us</span>
  <span m=''1483610''>a 2,</span> <span m=''1485490''>and</span> <span m=''1485870''>then</span>
  <span m=''1486010''>the</span> <span m=''1486100''>minus</span> <span m=''1486990''>sign</span>
  <span m=''1487370''>h</span> <span m=''1487770''>and</span> <span m=''1487920''>the</span>
  <span m=''1487990''>minus</span> <span m=''1488470''>sine</span> <span m=''1488830''>3h</span>
  <span m=''1490800''>combine</span> <span m=''1491470''>into</span> <span m=''1491930''>sign</span>
  <span m=''1492510''>2h</span> <span m=''1493200''>times,</span> <span m=''1494650''>I</span>
  <span m=''1494800''>think,</span> <span m=''1495140''>it''s</span> <span m=''1495310''>s</span>
  <span m=''1495540''>cosine</span> <span m=''1497230''>of</span> <span m=''1497850''>h</span>
  <span m=''1498340''>or</span> <span m=''1498460''>something,</span> <span m=''1500210''>it''s</span>
  <span m=''1500440''>that</span> <span m=''1503470''>eigenvector</span> <span m=''1504160''>that''s</span>
  <span m=''1504420''>near</span> <span m=''1504950''>zero.</span> <span m=''1507290''>But</span>
  <span m=''1507380''>the cosine</span> <span m=''1507930''>of</span> <span m=''1508050''>h</span>
  <span m=''1508320''>is</span> <span m=''1508480''>near</span> <span m=''1508680''>1.</span>
  <span m=''1510150''>Does</span> <span m=''1510310''>that</span> <span m=''1510500''>look</span>
  <span m=''1510690''>familiar?</span> <span m=''1511320''>That</span> <span m=''1512540''>combination</span>
  <span m=''1513230''>of</span> <span m=''1513380''>sine</span> <span m=''1513870''>h</span>
  <span m=''1514580''>and sine</span> <span m=''1515260''>3h</span> <span m=''1516610''>should</span>
  <span m=''1516910''>give</span> <span m=''1517180''>us</span> <span m=''1517600''>twice</span>
  <span m=''1519170''>sine</span> <span m=''1519570''>2h</span> <span m=''1520300''>times</span>
  <span m=''1520660''>some</span> <span m=''1521120''>cosine,</span> <span m=''1521760''>yep,</span>
  <span m=''1524900''>Elementary</span> <span m=''1526260''>trig</span> <span m=''1526770''>identity.</span>
  <span m=''1528320''>OK,</span> <span m=''1528720''>so</span> <span m=''1528940''>those</span>
  <span m=''1529270''>are</span> <span m=''1529450''>eigenvectors.</span> <span m=''1531000''>That''s</span>
  <span m=''1531270''>the</span> <span m=''1531400''>first</span> <span m=''1531750''>one,</span>
  <span m=''1532730''>the</span> <span m=''1532860''>next</span> <span m=''1533220''>one</span>
  <span m=''1533430''>would</span> <span m=''1533700''>have</span> <span m=''1534730''>h</span>
  <span m=''1535150''>times</span> <span m=''1536230''>the</span> <span m=''1536450''>k''th</span>
  <span m=''1536940''>one</span> <span m=''1537340''>would</span> <span m=''1537580''>have</span>
  <span m=''1537980''>h</span> <span m=''1538270''>times</span> <span m=''1538650''>k</span>
  <span m=''1540000''>instead</span> <span m=''1540500''>of</span> <span m=''1540900''>just</span>
  <span m=''1541200''>h</span> <span m=''1541530''>itself,</span> <span m=''1542260''>it</span>
  <span m=''1542430''>would</span> <span m=''1543080''>take</span> <span m=''1543420''>jumps</span>
  <span m=''1543880''>of</span> <span m=''1544100''>every</span> <span m=''1544460''>k</span>
  <span m=''1545900''>sine,</span> <span m=''1547200''>and</span> <span m=''1547430''>then</span>
  <span m=''1549430''>a</span> <span m=''1549560''>cosine</span> <span m=''1550340''>hk</span>
  <span m=''1551100''>would</span> <span m=''1551330''>show</span> <span m=''1551600''>up</span>
  <span m=''1551790''>there,</span> <span m=''1552560''>and</span> <span m=''1552880''>this</span>
  <span m=''1553080''>would</span> <span m=''1553280''>still</span> <span m=''1553540''>be</span>
  <span m=''1553680''>an</span> <span m=''1553820''>eigenvector.</span> <span m=''1556290''>OK.</span>
  <span m=''1559240''>I''m</span> <span m=''1559430''>making</span> <span m=''1559910''>a</span>
  <span m=''1560000''>little</span> <span m=''1560280''>bit</span> <span m=''1560550''>explicit</span>
  <span m=''1565010''>these</span> <span m=''1565330''>vectors,</span> <span m=''1566820''>but</span>
  <span m=''1567790''>the</span> <span m=''1567970''>main</span> <span m=''1568260''>point</span>
  <span m=''1568570''>is</span> <span m=''1569210''>they''re</span> <span m=''1569900''>sines,</span>
  <span m=''1570570''>they''re</span> <span m=''1570750''>discrete</span> <span m=''1571350''>sines</span>
  <span m=''1572320''>at</span> <span m=''1572560''>equally</span> <span m=''1573110''>spaced</span>
  <span m=''1573620''>points.</span> </p><p><span m=''1574570''>That''s</span> <span
  m=''1575030''>what</span> <span m=''1576020''>the</span> <span m=''1576170''>real</span>
  <span m=''1576600''>version</span> <span m=''1577090''>of</span> <span m=''1577230''>the</span>
  <span m=''1577360''>FFT</span> <span m=''1578780''>just</span> <span m=''1579780''>lives</span>
  <span m=''1580120''>on,</span> <span m=''1582600''>and</span> <span m=''1582800''>it</span>
  <span m=''1582870''>would</span> <span m=''1583040''>also</span> <span m=''1583370''>live</span>
  <span m=''1583630''>on</span> <span m=''1583830''>discrete</span> <span m=''1584310''>cosines</span>
  <span m=''1585020''>if</span> <span m=''1585170''>we</span> <span m=''1585300''>had</span>
  <span m=''1585470''>different</span> <span m=''1585840''>boundary</span> <span m=''1586210''>conditions,</span>
  <span m=''1586710''>we</span> <span m=''1586850''>could</span> <span m=''1587010''>do</span>
  <span m=''1587150''>those,</span> <span m=''1587650''>too.</span> <span m=''1588280''>So</span>
  <span m=''1588930''>this</span> <span m=''1589200''>isn''t</span> <span m=''1589530''>the</span>
  <span m=''1589650''>only --</span> <span m=''1591960''>these</span> <span m=''1592660''>zero</span>
  <span m=''1593020''>boundary</span> <span m=''1593450''>conditions</span> <span
  m=''1594030''>are</span> <span m=''1594170''>associated</span> <span m=''1594850''>with</span>
  <span m=''1595070''>the</span> <span m=''1595230''>name</span> <span m=''1595620''>of</span>
  <span m=''1596000''>Dirichlet,</span> <span m=''1600240''>where</span> <span m=''1600650''>zero</span>
  <span m=''1601060''>slopes</span> <span m=''1601780''>are</span> <span m=''1601940''>associated</span>
  <span m=''1602510''>with</span> <span m=''1602660''>the</span> <span m=''1602740''>name</span>
  <span m=''1603050''>of</span> <span m=''1603190''>Neumann,</span> <span m=''1604350''>and</span>
  <span m=''1604900''>both,</span> <span m=''1605810''>this</span> <span m=''1606100''>one</span>
  <span m=''1606350''>gives</span> <span m=''1606600''>sines,</span> <span m=''1607390''>Neumann</span>
  <span m=''1607950''>gives</span> <span m=''1608220''>cosines,</span> <span m=''1609830''>the</span>
  <span m=''1609980''>FFT</span> <span m=''1610900''>deals</span> <span m=''1611190''>with</span>
  <span m=''1611360''>both.</span> <span m=''1612160''>OK.</span> <span m=''1613600''>So,</span>
  <span m=''1613770''>that''s</span> <span m=''1614180''>the</span> <span m=''1616940''>fast</span>
  <span m=''1617340''>solution,</span> <span m=''1618720''>and</span> <span m=''1619060''>it</span>
  <span m=''1619150''>would</span> <span m=''1619340''>take</span> <span m=''1619740''>n</span>
  <span m=''1620170''>squared --</span> <span m=''1620840''>well</span> <span m=''1621540''>I</span>
  <span m=''1621800''>have</span> <span m=''1621970''>to</span> <span m=''1622090''>go</span>
  <span m=''1622210''>to</span> <span m=''1622380''>2d.</span> <span m=''1622890''>sorry,</span>
  <span m=''1624010''>I</span> <span m=''1624140''>guess</span> <span m=''1624430''>I</span>
  <span m=''1624550''>have</span> <span m=''1624750''>a</span> <span m=''1624830''>little</span>
  <span m=''1625110''>more</span> <span m=''1625330''>to</span> <span m=''1625470''>say</span>
  <span m=''1625810''>because</span> <span m=''1626240''>I</span> <span m=''1626390''>have</span>
  <span m=''1626660''>to</span> <span m=''1627510''>get</span> <span m=''1627860''>from</span>
  <span m=''1629140''>this</span> <span m=''1629430''>one-dimensional</span> <span
  m=''1632020''>second</span> <span m=''1632440''>difference</span> <span m=''1633040''>to</span>
  <span m=''1633190''>the</span> <span m=''1633340''>5.2-dimensional</span> <span
  m=''1635510''>second</span> <span m=''1635910''>difference,</span> <span m=''1636580''>and</span>
  <span m=''1636760''>that''s</span> <span m=''1637050''>what''s</span> <span m=''1637530''>going
  to</span> <span m=''1637820''>happen</span> <span m=''1638310''>over</span> <span
  m=''1638590''>here.</span> <span m=''1641080''>I</span> <span m=''1641180''>wrote</span>
  <span m=''1641490''>up</span> <span m=''1641720''>some</span> <span m=''1644160''>stuff</span>
  <span m=''1644530''>about</span> <span m=''1644940''>the</span> <span m=''1645080''>Kronecker</span>
  <span m=''1646400''>operation,</span> <span m=''1648060''>which</span> <span m=''1648400''>is</span>
  <span m=''1649290''>the</span> <span m=''1650150''>nifty</span> <span m=''1650630''>way</span>
  <span m=''1651490''>for</span> <span m=''1651660''>these</span> <span m=''1651940''>special</span>
  <span m=''1652370''>problems</span> <span m=''1653000''>to</span> <span m=''1653150''>go</span>
  <span m=''1653420''>from</span> <span m=''1654330''>1d</span> <span m=''1654830''>to</span>
  <span m=''1654980''>2d.</span> <span m=''1656740''>You</span> <span m=''1656880''>remember</span>
  <span m=''1659200''>the</span> <span m=''1659330''>deal,</span> <span m=''1660100''>that</span>
  <span m=''1660270''>k2d,</span> <span m=''1661400''>our</span> <span m=''1661620''>2d</span>
  <span m=''1662100''>matrix</span> <span m=''1662880''>was</span> <span m=''1664360''>this</span>
  <span m=''1664410''>Kronecker</span> <span m=''1665020''>product</span> <span m=''1666060''>of</span>
  <span m=''1668620''>k</span> <span m=''1669180''>and</span> <span m=''1669450''>i,</span>
  <span m=''1670760''>that</span> <span m=''1670960''>gave</span> <span m=''1671280''>us</span>
  <span m=''1671380''>second</span> <span m=''1671890''>differences</span> <span m=''1672600''>in</span>
  <span m=''1673050''>one</span> <span m=''1673310''>direction,</span> <span m=''1674410''>and</span>
  <span m=''1674600''>then</span> <span m=''1674720''>we</span> <span m=''1674870''>have</span>
  <span m=''1675110''>to add</span> <span m=''1675530''>in</span> <span m=''1675800''>the</span>
  <span m=''1675910''>Kronecker</span> <span m=''1676420''>product</span> <span m=''1676940''>of</span>
  <span m=''1677280''>i</span> <span m=''1677680''>and</span> <span m=''1677960''>k</span>
  <span m=''1679040''>to</span> <span m=''1679140''>get</span> <span m=''1679770''>second</span>
  <span m=''1680210''>differences</span> <span m=''1680750''>in</span> <span m=''1680880''>the</span>
  <span m=''1680970''>other</span> <span m=''1681250''>direction.</span> <span m=''1682150''>And</span>
  <span m=''1682350''>then</span> <span m=''1682970''>we</span> <span m=''1683110''>better</span>
  <span m=''1683440''>print,</span> <span m=''1685500''>because</span> <span m=''1685870''>that</span>
  <span m=''1686070''>matrix</span> <span m=''1686580''>is</span> <span m=''1686730''>going
  to</span> <span m=''1686960''>be</span> <span m=''1687120''>large,</span> <span
  m=''1687810''>I</span> <span m=''1687940''>don''t</span> <span m=''1688120''>want</span>
  <span m=''1688250''>to</span> <span m=''1688310''>[UNINTELLIGIBLE]</span> <span
  m=''1688610''>it,</span> <span m=''1692680''>yeah.</span> <span m=''1693660''>What''s</span>
  <span m=''1693970''>the</span> <span m=''1694080''>point?</span> </p><p><span m=''1695080''>The</span>
  <span m=''1695210''>point</span> <span m=''1695530''>is</span> <span m=''1695820''>that</span>
  <span m=''1696690''>if</span> <span m=''1696880''>I</span> <span m=''1697010''>know</span>
  <span m=''1697280''>the</span> <span m=''1697470''>eigenvectors</span> <span m=''1698450''>of</span>
  <span m=''1698890''>k,</span> <span m=''1699970''>then</span> <span m=''1700160''>I</span>
  <span m=''1700270''>can</span> <span m=''1700360''>find</span> <span m=''1700650''>the
  --</span> <span m=''1702390''>if</span> <span m=''1702600''>I</span> <span m=''1702690''>know</span>
  <span m=''1702870''>the</span> <span m=''1702990''>1d</span> <span m=''1703240''>eigenvectors,</span>
  <span m=''1704130''>I</span> <span m=''1704240''>can</span> <span m=''1704390''>find</span>
  <span m=''1704670''>the</span> <span m=''1704800''>2d</span> <span m=''1705180''>eigenvectors,</span>
  <span m=''1706280''>and</span> <span m=''1706560''>you</span> <span m=''1706690''>don''t</span>
  <span m=''1706910''>have</span> <span m=''1707080''>to</span> <span m=''1707190''>know</span>
  <span m=''1707390''>Kronecker</span> <span m=''1707870''>products</span> <span m=''1708400''>to</span>
  <span m=''1708510''>do</span> <span m=''1708690''>that.</span> <span m=''1709380''>All</span>
  <span m=''1709530''>you</span> <span m=''1709630''>have</span> <span m=''1709750''>to</span>
  <span m=''1709890''>do</span> <span m=''1710010''>is</span> <span m=''1710220''>just</span>
  <span m=''1710490''>make</span> <span m=''1710700''>a</span> <span m=''1711270''>sensible</span>
  <span m=''1711830''>guess,</span> <span m=''1712780''>so</span> <span m=''1712930''>the</span>
  <span m=''1713260''>eigenvectors</span> <span m=''1715970''>in</span> <span m=''1716390''>2d,</span>
  <span m=''1720860''>have</span> <span m=''1721080''>a</span> <span m=''1721150''>double</span>
  <span m=''1721560''>index,</span> <span m=''1722170''>k</span> <span m=''1722770''>and</span>
  <span m=''1723000''>l,</span> <span m=''1726580''>and</span> <span m=''1727010''>their</span>
  <span m=''1727230''>components</span> <span m=''1730250''>are</span> <span m=''1735190''>sines</span>
  <span m=''1736290''>in</span> <span m=''1736540''>one</span> <span m=''1736850''>direction</span>
  <span m=''1737430''>times</span> <span m=''1737860''>sines</span> <span m=''1738660''>in</span>
  <span m=''1738850''>the</span> <span m=''1738930''>other</span> <span m=''1739190''>direction.</span>
  <span m=''1740160''>So</span> <span m=''1740320''>what</span> <span m=''1740580''>are</span>
  <span m=''1740780''>those</span> <span m=''1741740''>sines,</span> <span m=''1742410''>there''s
  a</span> <span m=''1742680''>kh,</span> <span m=''1745030''>I</span> <span m=''1745250''>guess,</span>
  <span m=''1746390''>lh.</span> <span m=''1754080''>Those</span> <span m=''1754410''>are</span>
  <span m=''1754510''>the</span> <span m=''1754640''>first</span> <span m=''1755010''>components,</span>
  <span m=''1757490''>I</span> <span m=''1757620''>guess</span> <span m=''1757880''>I</span>
  <span m=''1757980''>have</span> <span m=''1758130''>to</span> <span m=''1758280''>tell</span>
  <span m=''1758500''>you</span> <span m=''1758620''>what</span> <span m=''1758860''>all</span>
  <span m=''1759130''>the</span> <span m=''1759570''>components</span> <span m=''1760170''>are:</span>
  <span m=''1760390''>k,</span> <span m=''1764620''>the</span> <span m=''1764760''>seventh</span>
  <span m=''1765360''>component</span> <span m=''1766000''>in</span> <span m=''1766110''>the
  x''th</span> <span m=''1766380''>direction,</span> <span m=''1766900''>there''d</span>
  <span m=''1767050''>be</span> <span m=''1767150''>a</span> <span m=''1767230''>factor</span>
  <span m=''1767640''>7,</span> <span m=''1768060''>so</span> <span m=''1768590''>kmh</span>
  <span m=''1771700''>sine</span> <span m=''1772240''>lnh.</span> <span m=''1774840''>This</span>
  <span m=''1775080''>is</span> <span m=''1775280''>the</span> <span m=''1776070''>mn</span>
  <span m=''1777960''>component</span> <span m=''1779680''>of</span> <span m=''1781300''>ykl.</span>
  <span m=''1788720''>It''s</span> <span m=''1788910''>just</span> <span m=''1789180''>what</span>
  <span m=''1789320''>we</span> <span m=''1789440''>had</span> <span m=''1789640''>in</span>
  <span m=''1789770''>1d,</span> <span m=''1790680''>in</span> <span m=''1790850''>1d</span>
  <span m=''1791190''>there</span> <span m=''1791330''>was</span> <span m=''1791490''>no</span>
  <span m=''1791750''>l,</span> <span m=''1793810''>the</span> <span m=''1793920''>components</span>
  <span m=''1794540''>were</span> <span m=''1794720''>just</span> <span m=''1795710''>sine</span>
  <span m=''1796510''>kmh.</span> <span m=''1798130''>Now</span> <span m=''1799130''>we''ve</span>
  <span m=''1799320''>got</span> <span m=''1799540''>two,</span> <span m=''1800560''>one</span>
  <span m=''1801790''>in</span> <span m=''1802190''>the</span> <span m=''1802510''>x</span>
  <span m=''1803660''>direction.</span> <span m=''1805320''>These</span> <span m=''1805580''>are</span>
  <span m=''1805670''>the</span> <span m=''1805800''>analogs</span> <span m=''1806430''>of</span>
  <span m=''1807780''>the --</span> <span m=''1809990''>the continuous</span> <span
  m=''1811450''>case</span> <span m=''1811920''>would</span> <span m=''1812170''>be</span>
  <span m=''1813400''>sine,</span> <span m=''1814980''>k</span> <span m=''1815310''>pi</span>
  <span m=''1815550''>x,</span> <span m=''1817220''>times</span> <span m=''1818750''>sine</span>
  <span m=''1820110''>l</span> <span m=''1820440''>pi</span> <span m=''1820700''>y.</span>
  <span m=''1824740''>Those</span> <span m=''1825200''>are</span> <span m=''1825300''>the</span>
  <span m=''1825420''>eigenvectors</span> <span m=''1826750''>as</span> <span m=''1827640''>eigenfunctions,</span>
  <span m=''1829380''>functions</span> <span m=''1829890''>of</span> <span m=''1829990''>x</span>
  <span m=''1830080''>and</span> <span m=''1830380''>y.</span> <span m=''1831000''>And</span>
  <span m=''1831300''>the</span> <span m=''1831420''>point</span> <span m=''1831800''>is</span>
  <span m=''1832120''>that,</span> <span m=''1832540''>once</span> <span m=''1832950''>again,</span>
  <span m=''1835300''>with</span> <span m=''1835440''>these</span> <span m=''1835760''>beautiful</span>
  <span m=''1836410''>matrices,</span> <span m=''1837520''>I</span> <span m=''1837710''>can</span>
  <span m=''1837930''>sample</span> <span m=''1839560''>these</span> <span m=''1840220''>at</span>
  <span m=''1840820''>the</span> <span m=''1841840''>equally</span> <span m=''1842280''>spaced</span>
  <span m=''1842680''>points,</span> <span m=''1843120''>and</span> <span m=''1843270''>I</span>
  <span m=''1843370''>get</span> <span m=''1844690''>discrete</span> <span m=''1845260''>sines</span>
  <span m=''1845870''>that</span> <span m=''1846080''>the</span> <span m=''1846240''>FFT</span>
  <span m=''1846960''>is</span> <span m=''1847940''>ready</span> <span m=''1848210''>to</span>
  <span m=''1848350''>go with,</span> <span m=''1849310''>OK.</span> <span m=''1854670''>I''m</span>
  <span m=''1855220''>giving</span> <span m=''1855670''>this</span> <span m=''1855890''>much</span>
  <span m=''1856230''>detail</span> <span m=''1859850''>partly</span> <span m=''1860180''>because</span>
  <span m=''1863880''>the</span> <span m=''1864140''>continuous</span> <span m=''1864770''>case,</span>
  <span m=''1865080''>of</span> <span m=''1865210''>course,</span> <span m=''1865610''>our</span>
  <span m=''1866910''>operators</span> <span m=''1867690''>d</span> <span m=''1867910''>second</span>
  <span m=''1868390''>by</span> <span m=''1868600''>the</span> <span m=''1869020''>dx</span>
  <span m=''1869320''>squared and</span> <span m=''1869580''>d</span> <span m=''1869730''>second</span>
  <span m=''1870170''>by</span> <span m=''1870400''>dy</span> <span m=''1870870''>squared,</span>
  <span m=''1872470''>and</span> <span m=''1873110''>the</span> <span m=''1873280''>whole</span>
  <span m=''1874850''>idea</span> <span m=''1876090''>of</span> <span m=''1876970''>separating</span>
  <span m=''1877820''>variables,</span> <span m=''1878900''>of</span> <span m=''1879090''>looking</span>
  <span m=''1879560''>for</span> <span m=''1880260''>solutions,</span> <span m=''1882110''>u
  --</span> <span m=''1884700''>here</span> <span m=''1884960''>is</span> <span m=''1885160''>the</span>
  <span m=''1885370''>eigenvalue</span> <span m=''1886140''>problem,</span> <span
  m=''1886950''>the</span> <span m=''1887060''>continuous</span> <span m=''1887730''>eigenvalue</span>
  <span m=''1888380''>problem.</span> <span m=''1888930''>The</span> <span m=''1889320''>Laplacian</span>
  <span m=''1890030''>of</span> <span m=''1890210''>u,</span> <span m=''1890670''>maybe</span>
  <span m=''1890920''>I</span> <span m=''1891010''>do</span> <span m=''1891220''>a</span>
  <span m=''1891300''>minus,</span> <span m=''1892300''>the</span> <span m=''1892470''>Laplacian</span>
  <span m=''1892860''>of u</span> <span m=''1893530''>equal</span> <span m=''1893850''>lambda</span>
  <span m=''1894320''>u,</span> <span m=''1895670''>and</span> <span m=''1896990''>that''s</span>
  <span m=''1897220''>a</span> <span m=''1897280''>partial</span> <span m=''1897710''>differential</span>
  <span m=''1898190''>equation,</span> <span m=''1898760''>usually</span> <span m=''1899450''>it''s</span>
  <span m=''1899680''>not</span> <span m=''1900870''>easy</span> <span m=''1901200''>to</span>
  <span m=''1901360''>solve,</span> <span m=''1902410''>but</span> <span m=''1902850''>if</span>
  <span m=''1903100''>I''m</span> <span m=''1903270''>on a</span> <span m=''1903620''>square,</span>
  <span m=''1905540''>and</span> <span m=''1905750''>I</span> <span m=''1905860''>have</span>
  <span m=''1906100''>zero</span> <span m=''1906490''>boundary</span> <span m=''1906910''>conditions,</span>
  <span m=''1908700''>then</span> <span m=''1909230''>I''ve</span> <span m=''1909420''>solved
  it,</span> <span m=''1910480''>by</span> <span m=''1910660''>separation</span> <span
  m=''1911370''>of</span> <span m=''1911450''>variables,</span> <span m=''1912430''>a
  function</span> <span m=''1912990''>of x</span> <span m=''1913350''>times</span>
  <span m=''1913620''>a</span> <span m=''1913730''>function</span> <span m=''1914170''>of</span>
  <span m=''1914280''>y.</span> <span m=''1915600''>And</span> <span m=''1915890''>that</span>
  <span m=''1915980''>function</span> <span m=''1916310''>of x</span> <span m=''1916780''>times</span>
  <span m=''1916950''>function</span> <span m=''1917440''>of y is</span> <span m=''1917920''>exactly</span>
  <span m=''1918440''>what</span> <span m=''1919150''>Kronecker</span> <span m=''1919580''>product</span>
  <span m=''1920110''>is</span> <span m=''1920290''>doing</span> <span m=''1920730''>for</span>
  <span m=''1921400''>matrices,</span> <span m=''1923170''>yep.</span> <span m=''1928730''>I</span>
  <span m=''1928840''>thought</span> <span m=''1929170''>maybe</span> <span m=''1929450''>this</span>
  <span m=''1929690''>is</span> <span m=''1931930''>good</span> <span m=''1932200''>to</span>
  <span m=''1932300''>know</span> <span m=''1932790''>when</span> <span m=''1933300''>the</span>
  <span m=''1933390''>problem</span> <span m=''1933840''>is</span> <span m=''1933970''>easy,</span>
  <span m=''1935960''>and</span> <span m=''1936150''>as</span> <span m=''1936280''>I</span>
  <span m=''1936410''>say,</span> <span m=''1936870''>the</span> <span m=''1937150''>possibility</span>
  <span m=''1938070''>of</span> <span m=''1938330''>using</span> <span m=''1938930''>the</span>
  <span m=''1939100''>easy</span> <span m=''1941740''>case</span> <span m=''1942070''>on</span>
  <span m=''1942220''>a</span> <span m=''1942320''>square</span> <span m=''1943750''>for</span>
  <span m=''1944570''>preconditioning</span> <span m=''1946330''>a</span> <span m=''1946470''>not</span>
  <span m=''1946780''>so</span> <span m=''1946930''>easy</span> <span m=''1947220''>case</span>
  <span m=''1948150''>is</span> <span m=''1948350''>attractive.</span> <span m=''1949560''>All
  right,</span> <span m=''1950390''>so</span> <span m=''1950540''>that''s</span> <span
  m=''1951270''>what</span> <span m=''1951490''>I</span> <span m=''1951560''>wanted</span>
  <span m=''1951920''>to</span> <span m=''1952030''>say</span> <span m=''1952390''>about</span>
  <span m=''1953350''>number</span> <span m=''1953660''>one,</span> <span m=''1954910''>that''s</span>
  <span m=''1955140''>the</span> <span m=''1955250''>main</span> <span m=''1957240''>suggestion,</span>
  <span m=''1958820''>and</span> <span m=''1960130''>again,</span> <span m=''1960650''>the</span>
  <span m=''1960790''>point</span> <span m=''1961220''>was</span> <span m=''1962990''>just</span>
  <span m=''1963250''>to</span> <span m=''1963360''>take</span> <span m=''1963640''>these</span>
  <span m=''1963920''>three</span> <span m=''1964140''>simple</span> <span m=''1964500''>steps,</span>
  <span m=''1966400''>provided</span> <span m=''1967860''>we</span> <span m=''1968070''>know</span>
  <span m=''1968350''>and</span> <span m=''1968510''>like</span> <span m=''1969280''>the</span>
  <span m=''1969860''>eigenvector.</span> <span m=''1971730''>Here</span> <span m=''1971880''>we</span>
  <span m=''1972070''>know</span> <span m=''1972330''>them</span> <span m=''1972680''>and</span>
  <span m=''1974190''>we</span> <span m=''1974340''>like</span> <span m=''1974600''>them</span>
  <span m=''1974750''>very</span> <span m=''1975000''>much,</span> <span m=''1975300''>because</span>
  <span m=''1975550''>they''re</span> <span m=''1975750''>those</span> <span m=''1976340''>discrete</span>
  <span m=''1976780''>sines.</span> </p><p><span m=''1977580''>OK,</span> <span m=''1978560''>now</span>
  <span m=''1979760''>just</span> <span m=''1980000''>to</span> <span m=''1980150''>finish</span>
  <span m=''1981220''>comes,</span> <span m=''1982490''>what''s</span> <span m=''1982810''>up</span>
  <span m=''1983050''>with</span> <span m=''1983410''>odd</span> <span m=''1983660''>even</span>
  <span m=''1984020''>reduction.</span> <span m=''1986480''>I''ll</span> <span m=''1986610''>use</span>
  <span m=''1986830''>the</span> <span m=''1987040''>same</span> <span m=''1988330''>1d</span>
  <span m=''1988820''>problem</span> <span m=''1989360''>first.</span> <span m=''1991040''>It</span>
  <span m=''1991540''>works</span> <span m=''1991890''>great</span> <span m=''1992240''>in
  --</span> <span m=''1993370''>that''s</span> <span m=''1993610''>not</span> <span
  m=''1993860''>good</span> <span m=''1994050''>english,</span> <span m=''1994440''>but</span>
  <span m=''1994630''>it</span> <span m=''1994770''>works</span> <span m=''1995660''>very</span>
  <span m=''1995980''>well</span> <span m=''1996960''>in</span> <span m=''1997690''>1d</span>
  <span m=''1999660''>odd</span> <span m=''1999850''>even</span> <span m=''2000190''>reduction,</span>
  <span m=''2000680''>you''ll</span> <span m=''2000870''>see</span> <span m=''2001650''>it,</span>
  <span m=''2002030''>you''ll see, oh boy,</span> <span m=''2002770''>simple</span>
  <span m=''2003170''>idea.</span> <span m=''2003980''>But</span> <span m=''2004240''>of</span>
  <span m=''2004360''>course,</span> <span m=''2004620''>don''t</span> <span m=''2004830''>forget</span>
  <span m=''2005230''>that</span> <span m=''2006260''>ordinary</span> <span m=''2006670''>elimination</span>
  <span m=''2007430''>is</span> <span m=''2007650''>a</span> <span m=''2008700''>breeze</span>
  <span m=''2009840''>with</span> <span m=''2010520''>a</span> <span m=''2010620''>tri-diagonal</span>
  <span m=''2011350''>matrix,</span> <span m=''2011870''>so</span> <span m=''2012000''>nothing</span>
  <span m=''2012450''>I</span> <span m=''2012580''>could</span> <span m=''2012810''>do</span>
  <span m=''2013210''>could</span> <span m=''2013360''>be</span> <span m=''2013520''>faster</span>
  <span m=''2014050''>than</span> <span m=''2014590''>that.</span> <span m=''2015240''>But</span>
  <span m=''2015430''>let''s</span> <span m=''2015650''>see</span> <span m=''2015860''>what</span>
  <span m=''2016160''>you</span> <span m=''2016310''>can</span> <span m=''2016490''>do.</span>
  <span m=''2017300''>I</span> <span m=''2017420''>just</span> <span m=''2017640''>want</span>
  <span m=''2017810''>to</span> <span m=''2017890''>write</span> <span m=''2018120''>down</span>
  <span m=''2018510''>the --</span> <span m=''2019220''>OK,</span> <span m=''2020250''>keep</span>
  <span m=''2020450''>your</span> <span m=''2021270''>eye</span> <span m=''2021620''>on</span>
  <span m=''2021960''>this</span> <span m=''2022910''>matrix,</span> <span m=''2025810''>so</span>
  <span m=''2025970''>I''m</span> <span m=''2026110''>going</span> <span m=''2026270''>to</span>
  <span m=''2026350''>write</span> <span m=''2027970''>out</span> <span m=''2028150''>the</span>
  <span m=''2028340''>equations.</span> <span m=''2029350''>So</span> <span m=''2029540''>it''ll</span>
  <span m=''2029710''>be</span> <span m=''2029960''>minus</span> <span m=''2030830''>u,</span>
  <span m=''2031880''>i</span> <span m=''2032230''>minus</span> <span m=''2032770''>2</span>
  <span m=''2033690''>plus</span> <span m=''2034140''>2ui</span> <span m=''2036020''>minus
  1</span> <span m=''2037500''>minus</span> <span m=''2038570''>ui,</span> <span m=''2039080''>that</span>
  <span m=''2039350''>would</span> <span m=''2039570''>be</span> <span m=''2039830''>fi</span>
  <span m=''2041120''>minus</span> <span m=''2041570''>1;</span> <span m=''2041950''>that</span>
  <span m=''2042100''>would</span> <span m=''2042240''>be</span> <span m=''2042340''>equation</span>
  <span m=''2042990''>number --</span> <span m=''2043650''>i</span> <span m=''2043840''>minus</span>
  <span m=''2044230''>1,</span> <span m=''2044610''>right</span> <span m=''2044960''>with</span>
  <span m=''2045150''>a</span> <span m=''2045210''>minus</span> <span m=''2045610''>one,</span>
  <span m=''2045960''>two</span> <span m=''2046600''>minus</span> <span m=''2046980''>1,</span>
  <span m=''2048090''>centered</span> <span m=''2048710''>there;</span> <span m=''2049900''>and</span>
  <span m=''2050120''>then</span> <span m=''2050320''>the</span> <span m=''2050410''>next</span>
  <span m=''2050770''>one</span> <span m=''2051070''>will</span> <span m=''2051300''>be</span>
  <span m=''2052240''>a</span> <span m=''2052400''>minus</span> <span m=''2053610''>ui</span>
  <span m=''2054600''>minus</span> <span m=''2054960''>1</span> <span m=''2055540''>plus</span>
  <span m=''2056290''>2ui --</span> <span m=''2057200''>I</span> <span m=''2058120''>better</span>
  <span m=''2058350''>move</span> <span m=''2058670''>this</span> <span m=''2058960''>guy</span>
  <span m=''2059560''>over</span> <span m=''2059920''>further --</span> <span m=''2064170''>minus</span>
  <span m=''2064920''>ui</span> <span m=''2065900''>plus</span> <span m=''2066330''>1,</span>
  <span m=''2067270''>that will</span> <span m=''2067700''>be</span> <span m=''2070050''>fi,</span>
  <span m=''2070620''>right?</span> <span m=''2071340''>That''s</span> <span m=''2071670''>equation</span>
  <span m=''2072190''>number</span> <span m=''2072470''>i,</span> <span m=''2073260''>and</span>
  <span m=''2073440''>now</span> <span m=''2073560''>I</span> <span m=''2073630''>just</span>
  <span m=''2073860''>want to</span> <span m=''2074040''>look at</span> <span m=''2074320''>equation</span>
  <span m=''2074790''>number,</span> <span m=''2075350''>the</span> <span m=''2075450''>next</span>
  <span m=''2075810''>equation,</span> <span m=''2076450''>minus</span> <span m=''2076960''>ui</span>
  <span m=''2078320''>plus</span> <span m=''2078650''>2ui</span> <span m=''2079900''>plus</span>
  <span m=''2080290''>1</span> <span m=''2080820''>minus</span> <span m=''2081370''>ui</span>
  <span m=''2082310''>plus</span> <span m=''2082710''>2</span> <span m=''2083470''>is</span>
  <span m=''2084100''>fi</span> <span m=''2084370''>plus</span> <span m=''2084600''>1.</span>
  </p><p><span m=''2089350''>So</span> <span m=''2089510''>I''ve</span> <span m=''2089640''>written</span>
  <span m=''2089940''>down</span> <span m=''2091860''>three</span> <span m=''2094080''>consecutive</span>
  <span m=''2094760''>equations,</span> <span m=''2095390''>three</span> <span m=''2096150''>consecutive</span>
  <span m=''2096880''>rows</span> <span m=''2097840''>from</span> <span m=''2098300''>my</span>
  <span m=''2102850''>simple</span> <span m=''2103280''>matrix:</span> <span m=''2104240''>a</span>
  <span m=''2104400''>row,</span> <span m=''2105280''>the next</span> <span m=''2105730''>row,</span>
  <span m=''2106430''>and</span> <span m=''2106540''>the next row.</span> <span m=''2109420''>So</span>
  <span m=''2109650''>the</span> <span m=''2109760''>right-hand</span> <span m=''2110250''>sides</span>
  <span m=''2110630''>are</span> <span m=''2110800''>coming</span> <span m=''2111140''>in</span>
  <span m=''2111280''>order,</span> <span m=''2112350''>and</span> <span m=''2113010''>the</span>
  <span m=''2113450''>diagonals</span> <span m=''2114470''>are</span> <span m=''2114740''>there,</span>
  <span m=''2115840''>and</span> <span m=''2116750''>if</span> <span m=''2116890''>I</span>
  <span m=''2116970''>look</span> <span m=''2117200''>at</span> <span m=''2117290''>that,</span>
  <span m=''2117520''>do</span> <span m=''2117600''>I</span> <span m=''2117730''>get</span>
  <span m=''2117930''>any</span> <span m=''2118130''>idea?</span> <span m=''2121400''>Well,</span>
  <span m=''2124670''>there</span> <span m=''2124850''>is</span> <span m=''2125010''>an</span>
  <span m=''2125120''>idea</span> <span m=''2125620''>here.</span> <span m=''2131900''>I''d</span>
  <span m=''2132150''>like</span> <span m=''2132380''>to</span> <span m=''2132500''>remove</span>
  <span m=''2134150''>these</span> <span m=''2136630''>guys,</span> <span m=''2137060''>the</span>
  <span m=''2137220''>ui</span> <span m=''2137570''>minus</span> <span m=''2137990''>1''s</span>
  <span m=''2138710''>and</span> <span m=''2139060''>the ui</span> <span m=''2139330''>plus</span>
  <span m=''2139680''>1''s,</span> <span m=''2139980''>so</span> <span m=''2140220''>that''s</span>
  <span m=''2140490''>where</span> <span m=''2140690''>this</span> <span m=''2140930''>word</span>
  <span m=''2141350''>odd</span> <span m=''2141770''>even</span> <span m=''2142960''>reduction</span>
  <span m=''2143600''>is</span> <span m=''2143770''>coming</span> <span m=''2144080''>in.</span>
  <span m=''2144210''>I''m</span> <span m=''2144360''>going to</span> <span m=''2144600''>reduce</span>
  <span m=''2145090''>this</span> <span m=''2145250''>system</span> <span m=''2146160''>by</span>
  <span m=''2146370''>keeping</span> <span m=''2146820''>only</span> <span m=''2147400''>every</span>
  <span m=''2148390''>second</span> <span m=''2148910''>unknown</span> <span m=''2149840''>and</span>
  <span m=''2150090''>eliminating</span> <span m=''2152500''>those.</span> <span m=''2153750''>How</span>
  <span m=''2153950''>to</span> <span m=''2154090''>do</span> <span m=''2154250''>that?</span>
  <span m=''2155480''>Well,</span> <span m=''2155770''>you</span> <span m=''2155960''>can</span>
  <span m=''2156150''>see</span> <span m=''2156340''>how</span> <span m=''2156550''>to</span>
  <span m=''2156670''>eliminate,</span> <span m=''2157260''>if</span> <span m=''2157380''>I''m</span>
  <span m=''2157540''>multiply</span> <span m=''2158040''>this</span> <span m=''2158280''>equation</span>
  <span m=''2158790''>by</span> <span m=''2159020''>2.</span> <span m=''2161050''>If</span>
  <span m=''2161390''>I</span> <span m=''2161490''>multiply</span> <span m=''2161920''>that</span>
  <span m=''2162140''>middle</span> <span m=''2162470''>equation</span> <span m=''2163090''>by</span>
  <span m=''2163310''>2,</span> <span m=''2164430''>that</span> <span m=''2164650''>becomes</span>
  <span m=''2165060''>a</span> <span m=''2165160''>4,</span> <span m=''2165840''>this</span>
  <span m=''2166020''>becomes</span> <span m=''2166410''>a</span> <span m=''2166490''>minus</span>
  <span m=''2166960''>2,</span> <span m=''2167380''>this</span> <span m=''2167590''>becomes</span>
  <span m=''2168000''>a</span> <span m=''2168100''>2,</span> <span m=''2168910''>and</span>
  <span m=''2169140''>now</span> <span m=''2169360''>what</span> <span m=''2169570''>shall</span>
  <span m=''2169760''>I</span> <span m=''2169860''>do?</span> <span m=''2172950''>Add.</span>
  <span m=''2174720''>If</span> <span m=''2174870''>I</span> <span m=''2174970''>add
  the</span> <span m=''2175300''>equations</span> <span m=''2175980''>together,</span>
  <span m=''2176960''>I</span> <span m=''2177150''>get</span> <span m=''2177830''>minus</span>
  <span m=''2178590''>u,</span> <span m=''2179380''>i</span> <span m=''2179540''>minus</span>
  <span m=''2179770''>2,</span> <span m=''2180510''>these</span> <span m=''2180810''>cancel,</span>
  <span m=''2181380''>that</span> <span m=''2181620''>was</span> <span m=''2181800''>the</span>
  <span m=''2181900''>point</span> <span m=''2182900''>plus</span> <span m=''2183780''>4</span>
  <span m=''2184300''>minus</span> <span m=''2184690''>a</span> <span m=''2184780''>couple,</span>
  <span m=''2185270''>so</span> <span m=''2185450''>that''s</span> <span m=''2185920''>2</span>
  <span m=''2186670''>ui''s</span> <span m=''2189160''>minus</span> <span m=''2189920''>this</span>
  <span m=''2190190''>guy,</span> <span m=''2190550''>ui</span> <span m=''2191640''>minus</span>
  <span m=''2192150''>2</span> <span m=''2192890''>is</span> <span m=''2193610''>that</span>
  <span m=''2193990''>sum</span> <span m=''2194510''>fi</span> <span m=''2195570''>minus</span>
  <span m=''2196030''>1,</span> <span m=''2196600''>2</span> <span m=''2197870''>fi''s</span>
  <span m=''2201810''>and</span> <span m=''2202920''>fi</span> <span m=''2203270''>plus</span>
  <span m=''2204200''>1.</span> <span m=''2207270''>Well,</span> <span m=''2207750''>sorry</span>
  <span m=''2208120''>it''s</span> <span m=''2208290''>squeezed</span> <span m=''2208720''>down</span>
  <span m=''2208970''>here,</span> <span m=''2209250''>but</span> <span m=''2209520''>this</span>
  <span m=''2209730''>is</span> <span m=''2209900''>the</span> <span m=''2210670''>point.</span>
  </p><p><span m=''2212680''>The main</span> <span m=''2213140''>point</span> <span
  m=''2213590''>is</span> <span m=''2214700''>look</span> <span m=''2214960''>at</span>
  <span m=''2215080''>this.</span> <span m=''2216800''>What</span> <span m=''2217640''>do</span>
  <span m=''2217700''>we</span> <span m=''2217830''>have?</span> <span m=''2220050''>We''ve</span>
  <span m=''2220270''>got</span> <span m=''2220520''>a</span> <span m=''2220620''>typical</span>
  <span m=''2221200''>equation,</span> <span m=''2223160''>but</span> <span m=''2223390''>now</span>
  <span m=''2226560''>we''ve</span> <span m=''2226880''>removed</span> <span m=''2227600''>half</span>
  <span m=''2227880''>the</span> <span m=''2227980''>unknown.</span> <span m=''2229720''>The</span>
  <span m=''2229830''>problem</span> <span m=''2230280''>is</span> <span m=''2230420''>now</span>
  <span m=''2230750''>half-sized.</span> <span m=''2232030''>We''ve</span> <span m=''2232250''>only</span>
  <span m=''2232530''>got</span> <span m=''2232790''>the</span> <span m=''2232870''>even-numbered</span>
  <span m=''2234420''>unknowns</span> <span m=''2236450''>at</span> <span m=''2236870''>a</span>
  <span m=''2237080''>small</span> <span m=''2237720''>cost</span> <span m=''2238350''>in</span>
  <span m=''2240060''>updating</span> <span m=''2240760''>the</span> <span m=''2240890''>right-hand</span>
  <span m=''2241410''>side,</span> <span m=''2244590''>and</span> <span m=''2244860''>the</span>
  <span m=''2244940''>problem''s</span> <span m=''2245290''>cut</span> <span m=''2245490''>in</span>
  <span m=''2245620''>half.</span> <span m=''2247280''>So</span> <span m=''2247440''>that''s</span>
  <span m=''2247760''>this</span> <span m=''2247950''>odd</span> <span m=''2248320''>even</span>
  <span m=''2248740''>reduction,</span> <span m=''2250250''>and</span> <span m=''2252420''>it</span>
  <span m=''2252760''>cuts</span> <span m=''2253080''>a</span> <span m=''2253160''>problem</span>
  <span m=''2253580''>in</span> <span m=''2253720''>half,</span> <span m=''2254090''>and</span>
  <span m=''2254230''>everybody</span> <span m=''2255080''>knows</span> <span m=''2255400''>right</span>
  <span m=''2255650''>away</span> <span m=''2255960''>what</span> <span m=''2256210''>to</span>
  <span m=''2256340''>do</span> <span m=''2256530''>next.</span> <span m=''2258820''>The</span>
  <span m=''2259300''>one</span> <span m=''2260040''>mantra</span> <span m=''2260460''>of</span>
  <span m=''2260840''>computer</span> <span m=''2261360''>science,</span> <span m=''2261930''>&quot;Do</span>
  <span m=''2262080''>it</span> <span m=''2262200''>again.&quot;</span> <span m=''2263670''>So</span>
  <span m=''2265470''>that</span> <span m=''2266380''>is</span> <span m=''2266550''>the</span>
  <span m=''2266690''>same</span> <span m=''2267050''>problem</span> <span m=''2267540''>on</span>
  <span m=''2267760''>the</span> <span m=''2268150''>even,</span> <span m=''2268760''>we</span>
  <span m=''2268910''>do</span> <span m=''2269090''>it</span> <span m=''2269220''>again,</span>
  <span m=''2270010''>so</span> <span m=''2271260''>I</span> <span m=''2271400''>should</span>
  <span m=''2271680''>really</span> <span m=''2271910''>call it</span> <span m=''2272490''>cyclic</span>
  <span m=''2273730''>reduction,</span> <span m=''2274360''>we</span> <span m=''2274560''>just</span>
  <span m=''2274670''>cycle</span> <span m=''2275780''>with</span> <span m=''2275990''>this</span>
  <span m=''2276270''>reduction,</span> <span m=''2277440''>and</span> <span m=''2277720''>in</span>
  <span m=''2277870''>the end,</span> <span m=''2278430''>we</span> <span m=''2278620''>have</span>
  <span m=''2279200''>a</span> <span m=''2280080''>2</span> <span m=''2280240''>by</span>
  <span m=''2280470''>2</span> <span m=''2280660''>problem.</span> <span m=''2284700''>That</span>
  <span m=''2284930''>seems</span> <span m=''2285260''>pretty</span> <span m=''2285580''>smart,</span>
  <span m=''2286650''>pretty</span> <span m=''2286940''>successful</span> <span m=''2287620''>move,</span>
  <span m=''2290200''>and</span> <span m=''2290590''>I</span> <span m=''2290670''>guess</span>
  <span m=''2290940''>if</span> <span m=''2291090''>we</span> <span m=''2291230''>do
  an</span> <span m=''2291510''>operation</span> <span m=''2292180''>count,</span>
  <span m=''2292730''>well,</span> <span m=''2293750''>I</span> <span m=''2293860''>haven''t</span>
  <span m=''2294180''>thought</span> <span m=''2294420''>that</span> <span m=''2294650''>through.</span>
  <span m=''2294970''>What</span> <span m=''2295210''>does</span> <span m=''2295330''>the</span>
  <span m=''2295440''>operation</span> <span m=''2296050''>count</span> <span m=''2296400''>look</span>
  <span m=''2296650''>like?</span> <span m=''2298530''>It</span> <span m=''2298720''>must</span>
  <span m=''2299070''>be</span> <span m=''2299290''>pretty</span> <span m=''2299980''>quick,</span>
  <span m=''2300590''>right?</span> <span m=''2301860''>Well,</span> <span m=''2302260''>undoubtedly</span>
  <span m=''2302870''>we''re</span> <span m=''2303050''>solving</span> <span m=''2303580''>this</span>
  <span m=''2303850''>linear</span> <span m=''2304250''>system</span> <span m=''2305200''>in
  o</span> <span m=''2306120''>of</span> <span m=''2306380''>n</span> <span m=''2306560''>steps.</span>
  <span m=''2307620''>Well,</span> <span m=''2308550''>no</span> <span m=''2308750''>big</span>
  <span m=''2309010''>surprise</span> <span m=''2309610''>to</span> <span m=''2309730''>be</span>
  <span m=''2309850''>able</span> <span m=''2310070''>to</span> <span m=''2310160''>deal</span>
  <span m=''2310380''>with</span> <span m=''2310520''>that</span> <span m=''2310760''>matrix</span>
  <span m=''2311750''>in</span> <span m=''2312150''>o of</span> <span m=''2312510''>n</span>
  <span m=''2313310''>steps,</span> <span m=''2313960''>because</span> <span m=''2315210''>elimination</span>
  <span m=''2315980''>would</span> <span m=''2316170''>take</span> <span m=''2316430''>o</span>
  <span m=''2316630''>of n</span> <span m=''2317290''>steps,</span> <span m=''2317740''>it''s</span>
  <span m=''2318010''>size</span> <span m=''2318460''>n,</span> <span m=''2319410''>but</span>
  <span m=''2319610''>it''s</span> <span m=''2319800''>bandwith</span> <span m=''2320460''>is</span>
  <span m=''2320610''>1,</span> <span m=''2321430''>so</span> <span m=''2322850''>2n</span>
  <span m=''2323390''>or</span> <span m=''2323530''>something</span> <span m=''2323960''>steps</span>
  <span m=''2324390''>would</span> <span m=''2324600''>do</span> <span m=''2324770''>it,</span>
  <span m=''2325500''>and</span> <span m=''2325940''>maybe,</span> <span m=''2326280''>I</span>
  <span m=''2326410''>don''t</span> <span m=''2326600''>know</span> <span m=''2326670''>how</span>
  <span m=''2326750''>many</span> <span m=''2326970''>steps</span> <span m=''2327330''>we</span>
  <span m=''2327490''>have</span> <span m=''2327730''>here.</span> <span m=''2330090''>I</span>
  <span m=''2330220''>guess,</span> <span m=''2331020''>when</span> <span m=''2331290''>we</span>
  <span m=''2331420''>cut</span> <span m=''2331730''>it</span> <span m=''2331890''>in</span>
  <span m=''2332050''>half</span> <span m=''2333080''>that</span> <span m=''2333400''>required</span>
  <span m=''2334020''>us</span> <span m=''2334210''>to</span> <span m=''2334370''>do</span>
  <span m=''2334880''>that</span> <span m=''2335150''>much.</span> <span m=''2336370''>It''s</span>
  <span m=''2337210''>order</span> <span m=''2337560''>n,</span> <span m=''2340100''>it''s</span>
  <span m=''2340350''>order</span> <span m=''2343090''>n.</span> </p><p><span m=''2343920''>So</span>
  <span m=''2346280''>the</span> <span m=''2346900''>key</span> <span m=''2347210''>question</span>
  <span m=''2347680''>is,</span> <span m=''2348270''>can</span> <span m=''2348450''>we</span>
  <span m=''2348580''>do</span> <span m=''2348710''>it</span> <span m=''2348910''>2d?</span>
  <span m=''2350580''>Can</span> <span m=''2350770''>we</span> <span m=''2350910''>do</span>
  <span m=''2351100''>the</span> <span m=''2351250''>same</span> <span m=''2351650''>thing</span>
  <span m=''2351930''>in</span> <span m=''2352550''>2d?</span> <span m=''2353790''>So</span>
  <span m=''2353990''>I</span> <span m=''2354100''>want to</span> <span m=''2354340''>follow</span>
  <span m=''2354760''>that</span> <span m=''2355280''>plan</span> <span m=''2356660''>in</span>
  <span m=''2357330''>two</span> <span m=''2357550''>dimensions</span> <span m=''2360330''>where</span>
  <span m=''2360750''>now</span> <span m=''2361630''>u</span> <span m=''2362160''>will</span>
  <span m=''2362480''>be</span> <span m=''2364260''>a</span> <span m=''2364360''>whole</span>
  <span m=''2364730''>row</span> <span m=''2364980''>at</span> <span m=''2365120''>a</span>
  <span m=''2365220''>time,</span> <span m=''2365960''>so</span> <span m=''2366170''>I''m</span>
  <span m=''2366300''>doing</span> <span m=''2366560''>block</span> <span m=''2367060''>2d,</span>
  <span m=''2367920''>block</span> <span m=''2368310''>2d.</span> <span m=''2370700''>So,</span>
  <span m=''2371260''>can</span> <span m=''2371440''>I</span> <span m=''2371500''>write</span>
  <span m=''2371760''>down</span> <span m=''2372010''>the</span> <span m=''2372110''>equations</span>
  <span m=''2372700''>in</span> <span m=''2372910''>block</span> <span m=''2374140''>2d</span>
  <span m=''2374430''>for</span> <span m=''2375130''>whole</span> <span m=''2375510''>rows,</span>
  <span m=''2376030''>so</span> <span m=''2376240''>ui</span> <span m=''2376830''>is</span>
  <span m=''2377000''>the</span> <span m=''2377160''>vector?</span> <span m=''2379800''>So</span>
  <span m=''2380400''>now</span> <span m=''2380650''>this</span> <span m=''2380830''>is</span>
  <span m=''2381030''>the</span> <span m=''2381190''>2d</span> <span m=''2381590''>problem,</span>
  <span m=''2382590''>so</span> <span m=''2382790''>it''ll</span> <span m=''2382950''>be</span>
  <span m=''2383100''>minus</span> <span m=''2383860''>the</span> <span m=''2383980''>identity,</span>
  <span m=''2385450''>where</span> <span m=''2385690''>instead</span> <span m=''2386060''>of</span>
  <span m=''2386170''>instead</span> <span m=''2386540''>of</span> <span m=''2386640''>1,</span>
  <span m=''2386990''>I</span> <span m=''2387100''>have</span> <span m=''2387220''>to</span>
  <span m=''2387320''>write</span> <span m=''2387580''>the</span> <span m=''2387660''>identity,</span>
  <span m=''2388860''>ui</span> <span m=''2390570''>minus</span> <span m=''2391040''>2</span>
  <span m=''2391600''>and</span> <span m=''2391990''>2k,</span> <span m=''2393840''>right?</span>
  <span m=''2396800''>Oh</span> <span m=''2396930''>no,</span> <span m=''2397170''>what</span>
  <span m=''2397420''>is</span> <span m=''2397690''>the</span> <span m=''2398590''>middle
  --</span> <span m=''2399050''>what''s</span> <span m=''2399330''>on</span> <span
  m=''2399560''>the --</span> <span m=''2403650''>so</span> <span m=''2405060''>multiplying</span>
  <span m=''2405630''>ui,</span> <span m=''2407210''>ui</span> <span m=''2407540''>minus</span>
  <span m=''2407920''>1.</span> <span m=''2408120''>I</span> <span m=''2408160''>wanted</span>
  <span m=''2408490''>to</span> <span m=''2408680''>just say</span> <span m=''2408900''>the</span>
  <span m=''2409060''>same</span> <span m=''2409310''>thing,</span> <span m=''2409540''>but</span>
  <span m=''2410060''>I</span> <span m=''2410130''>have</span> <span m=''2410240''>to</span>
  <span m=''2410360''>write</span> <span m=''2410630''>down</span> <span m=''2410960''>the
  --</span> <span m=''2413830''>this</span> <span m=''2413980''>is</span> <span m=''2414090''>going
  to</span> <span m=''2414310''>be</span> <span m=''2414460''>n</span> <span m=''2414730''>squared</span>
  <span m=''2415300''>equations,</span> <span m=''2416270''>n</span> <span m=''2416510''>at</span>
  <span m=''2416610''>a</span> <span m=''2416730''>time,</span> <span m=''2417500''>a
  whole</span> <span m=''2417770''>row</span> <span m=''2418130''>at</span> <span
  m=''2418220''>a</span> <span m=''2418300''>time,</span> <span m=''2419720''>and</span>
  <span m=''2420180''>what''s</span> <span m=''2420610''>on</span> <span m=''2420770''>the</span>
  <span m=''2420890''>diagonal</span> <span m=''2422030''>of</span> <span m=''2422550''>k2d?</span>
  <span m=''2423050''>Not</span> <span m=''2424980''>2k.</span> <span m=''2427310''>It''s</span>
  <span m=''2429420''>2i,</span> <span m=''2430440''>is</span> <span m=''2430590''>it</span>
  <span m=''2430760''>2i</span> <span m=''2431240''>plus</span> <span m=''2431520''>k?</span>
  <span m=''2432190''>Yeah.</span> <span m=''2432800''>Yeah,</span> <span m=''2433290''>k
  plus</span> <span m=''2433810''>2i.</span> <span m=''2436150''>Isn''t</span> <span
  m=''2436430''>that</span> <span m=''2436620''>what</span> <span m=''2436820''>we</span>
  <span m=''2436960''>have</span> <span m=''2437790''>on</span> <span m=''2438040''>the</span>
  <span m=''2438160''>diagonal</span> <span m=''2438960''>of</span> <span m=''2439820''>k2d1</span>
  <span m=''2442860''>times</span> <span m=''2443220''>ui</span> <span m=''2443910''>minus</span>
  <span m=''2444410''>1</span> <span m=''2445580''>minus</span> <span m=''2446190''>iui</span>
  <span m=''2450210''>is</span> <span m=''2450420''>equal</span> <span m=''2450890''>to</span>
  <span m=''2451060''>some --</span> <span m=''2453960''>that''s</span> <span m=''2454190''>a</span>
  <span m=''2454270''>whole</span> <span m=''2454450''>row</span> <span m=''2454720''>at</span>
  <span m=''2454790''>a</span> <span m=''2454870''>time.</span> <span m=''2455670''>These</span>
  <span m=''2455950''>are</span> <span m=''2456060''>all</span> <span m=''2456260''>vectors</span>
  <span m=''2456950''>with</span> <span m=''2457110''>n</span> <span m=''2457380''>components</span>
  <span m=''2457990''>now,</span> <span m=''2459330''>right?</span> <span m=''2462320''>The</span>
  <span m=''2462470''>minus</span> <span m=''2462970''>i, the 2i,</span> <span m=''2464320''>and</span>
  <span m=''2464580''>the</span> <span m=''2464660''>minus</span> <span m=''2465130''>i</span>
  <span m=''2465590''>are</span> <span m=''2465880''>the</span> <span m=''2466050''>second</span>
  <span m=''2466500''>differences</span> <span m=''2467760''>of</span> <span m=''2467970''>one</span>
  <span m=''2468390''>of</span> <span m=''2468550''>rows;</span> <span m=''2469390''>their</span>
  <span m=''2469860''>difference is</span> <span m=''2470420''>in</span> <span m=''2470530''>the</span>
  <span m=''2470630''>vertical</span> <span m=''2471060''>direction,</span> <span
  m=''2471970''>and</span> <span m=''2472220''>this</span> <span m=''2472500''>kui</span>
  <span m=''2474050''>the</span> <span m=''2474190''>second</span> <span m=''2474560''>difference
  is</span> <span m=''2475130''>along</span> <span m=''2475530''>the</span> <span
  m=''2475620''>row.</span> </p><p><span m=''2479340''>OK,</span> <span m=''2480060''>so</span>
  <span m=''2480300''>same</span> <span m=''2480660''>equation</span> <span m=''2481310''>at</span>
  <span m=''2481720''>the</span> <span m=''2481850''>next</span> <span m=''2482400''>row.</span>
  <span m=''2483160''>So</span> <span m=''2483310''>the</span> <span m=''2483420''>next</span>
  <span m=''2483690''>row</span> <span m=''2484000''>is</span> <span m=''2484270''>minus</span>
  <span m=''2484660''>i,</span> <span m=''2485810''>ui</span> <span m=''2486230''>minus</span>
  <span m=''2486550''>1,</span> <span m=''2488630''>k</span> <span m=''2489120''>plus</span>
  <span m=''2489700''>2ui,</span> <span m=''2494060''>ui,</span> <span m=''2494880''>because</span>
  <span m=''2495060''>that''s</span> <span m=''2495350''>now</span> <span m=''2495520''>the</span>
  <span m=''2495670''>diagonal</span> <span m=''2496240''>block</span> <span m=''2497020''>minus</span>
  <span m=''2497550''>iui</span> <span m=''2498900''>plus</span> <span m=''2499300''>1</span>
  <span m=''2500100''>is</span> <span m=''2500750''>fi</span> <span m=''2501470''>plus</span>
  <span m=''2501850''>1,</span> <span m=''2502760''>and</span> <span m=''2503180''>it''s</span>
  <span m=''2503320''>just</span> <span m=''2503510''>taking</span> <span m=''2503760''>a</span>
  <span m=''2503850''>second</span> <span m=''2504280''>to</span> <span m=''2504370''>write</span>
  <span m=''2504780''>this</span> <span m=''2505090''>one.</span> <span m=''2506640''>This
  is</span> <span m=''2507000''>k</span> <span m=''2507320''>plus</span> <span m=''2507720''>2i,</span>
  <span m=''2509600''>ui</span> <span m=''2509970''>plus</span> <span m=''2510280''>1,</span>
  <span m=''2511680''>minus</span> <span m=''2512830''>i</span> <span m=''2513660''>ui</span>
  <span m=''2514160''>plus</span> <span m=''2514440''>2</span> <span m=''2515510''>is</span>
  <span m=''2516580''>fi</span> <span m=''2516790''>plus 2,</span> <span m=''2517820''>OK.</span>
  <span m=''2521290''>Exactly</span> <span m=''2521850''>the</span> <span m=''2521990''>same,</span>
  <span m=''2523610''>but</span> <span m=''2523800''>now</span> <span m=''2526520''>a</span>
  <span m=''2526680''>row</span> <span m=''2526960''>at</span> <span m=''2527060''>a</span>
  <span m=''2527150''>time</span> <span m=''2527510''>in</span> <span m=''2527680''>2d.</span>
  <span m=''2528980''>So</span> <span m=''2529540''>the</span> <span m=''2529760''>same</span>
  <span m=''2530070''>idea is</span> <span m=''2530470''>going</span> <span m=''2530620''>to</span>
  <span m=''2530700''>work,</span> <span m=''2530970''>right,</span> <span m=''2531620''>what</span>
  <span m=''2531790''>do</span> <span m=''2531890''>I</span> <span m=''2531990''>do?</span>
  <span m=''2533280''>I</span> <span m=''2533390''>want</span> <span m=''2533760''>to</span>
  <span m=''2534140''>cancel</span> <span m=''2534840''>this,</span> <span m=''2536420''>so</span>
  <span m=''2536590''>I</span> <span m=''2536700''>multiply</span> <span m=''2537210''>that</span>
  <span m=''2537470''>row</span> <span m=''2537800''>by</span> <span m=''2537980''>k</span>
  <span m=''2538390''>plus</span> <span m=''2538630''>2i.</span> <span m=''2540990''>Before</span>
  <span m=''2541350''>I</span> <span m=''2541430''>multiplied</span> <span m=''2541940''>it</span>
  <span m=''2542110''>by</span> <span m=''2542320''>2,</span> <span m=''2542620''>but</span>
  <span m=''2542840''>now</span> <span m=''2543060''>I</span> <span m=''2543130''>have</span>
  <span m=''2543310''>to</span> <span m=''2543410''>multiply</span> <span m=''2543900''>it
  by</span> <span m=''2544170''>k plus</span> <span m=''2544780''>2i</span> <span
  m=''2546300''>times</span> <span m=''2546750''>the</span> <span m=''2546840''>row,</span>
  <span m=''2548430''>the</span> <span m=''2548790''>whole</span> <span m=''2549020''>row.</span>
  <span m=''2552350''>So</span> <span m=''2552550''>when</span> <span m=''2552710''>I</span>
  <span m=''2552790''>do</span> <span m=''2552950''>that</span> <span m=''2553180''>this</span>
  <span m=''2553370''>cancels,</span> <span m=''2554860''>so</span> <span m=''2555030''>I</span>
  <span m=''2555120''>have</span> <span m=''2555380''>minus</span> <span m=''2556040''>this,</span>
  <span m=''2556480''>this</span> <span m=''2556980''>guy</span> <span m=''2557900''>wasn''t</span>
  <span m=''2558310''>affected.</span> <span m=''2560240''>And</span> <span m=''2560930''>this</span>
  <span m=''2562090''>will</span> <span m=''2562290''>cancel,</span> <span m=''2563120''>the</span>
  <span m=''2563240''>k</span> <span m=''2563530''>plus</span> <span m=''2563740''>2i</span>
  <span m=''2564100''>will</span> <span m=''2564260''>cancel</span> <span m=''2564680''>this</span>
  <span m=''2564880''>one,</span> <span m=''2565070''>just</span> <span m=''2565550''>as</span>
  <span m=''2565740''>before.</span> <span m=''2566460''>This</span> <span m=''2566690''>will</span>
  <span m=''2566850''>not</span> <span m=''2567100''>be</span> <span m=''2567220''>affected,</span>
  <span m=''2571330''>ui</span> <span m=''2571930''>plus</span> <span m=''2572250''>2,</span>
  <span m=''2573640''>and</span> <span m=''2576130''>I</span> <span m=''2576890''>have</span>
  <span m=''2577150''>fi</span> <span m=''2578890''>and</span> <span m=''2580380''>k</span>
  <span m=''2580800''>plus</span> <span m=''2580970''>2i,</span> <span m=''2582960''>fi</span>
  <span m=''2583270''>plus</span> <span m=''2584670''>one</span> <span m=''2585920''>and</span>
  <span m=''2586500''>fi</span> <span m=''2586900''>plus</span> <span m=''2587220''>2.</span>
  <span m=''2590830''>That</span> <span m=''2590980''>should</span> <span m=''2591220''>have</span>
  <span m=''2591340''>been</span> <span m=''2591470''>i</span> <span m=''2591660''>minus</span>
  <span m=''2592050''>1,</span> <span m=''2593340''>and</span> <span m=''2593650''>this</span>
  <span m=''2593720''>should</span> <span m=''2593970''>have</span> <span m=''2594080''>been</span>
  <span m=''2594230''>i,</span> <span m=''2594640''>and</span> <span m=''2594800''>this</span>
  <span m=''2594870''>should</span> <span m=''2595060''>have</span> <span m=''2595150''>been</span>
  <span m=''2595280''>i</span> <span m=''2595480''>plus</span> <span m=''2595890''>1,</span>
  <span m=''2596220''>sorry,</span> <span m=''2598880''>mis-labeled</span> <span m=''2599810''>label</span>
  <span m=''2600370''>the</span> <span m=''2600840''>f''s,</span> <span m=''2602570''>but</span>
  <span m=''2603140''>no</span> <span m=''2603370''>big</span> <span m=''2603640''>deal.</span>
  <span m=''2604630''>The</span> <span m=''2604770''>point</span> <span m=''2605100''>is</span>
  <span m=''2605250''>the</span> <span m=''2605390''>left</span> <span m=''2605680''>side,</span>
  <span m=''2606880''>and</span> <span m=''2607260''>the</span> <span m=''2607340''>point</span>
  <span m=''2607650''>is</span> <span m=''2607820''>what''s</span> <span m=''2608110''>in</span>
  <span m=''2608270''>that</span> <span m=''2609730''>space.</span> <span m=''2612860''>What</span>
  <span m=''2613090''>goes</span> <span m=''2613340''>in</span> <span m=''2613450''>that</span>
  <span m=''2613650''>space?</span> <span m=''2614080''>Well,</span> <span m=''2615250''>it''s</span>
  <span m=''2615600''>minus</span> <span m=''2615990''>i,</span> <span m=''2617510''>k</span>
  <span m=''2617770''>plus</span> <span m=''2618060''>2i</span> <span m=''2618490''>squared,</span>
  <span m=''2620240''>minus</span> <span m=''2620620''>i,</span> <span m=''2621140''>so</span>
  <span m=''2621360''>this</span> <span m=''2621580''>is</span> <span m=''2624880''>k
  plus</span> <span m=''2625460''>2i</span> <span m=''2626040''>squared,</span> <span
  m=''2626610''>which</span> <span m=''2626880''>before</span> <span m=''2627770''>was</span>
  <span m=''2628110''>so</span> <span m=''2628290''>easy,</span> <span m=''2629670''>and</span>
  <span m=''2630130''>then</span> <span m=''2630340''>the</span> <span m=''2630420''>minus</span>
  <span m=''2630780''>i,</span> <span m=''2631170''>and the</span> <span m=''2631250''>minus</span>
  <span m=''2631430''>i  is</span> <span m=''2632010''>the minus</span> <span m=''2632370''>2i</span>
  <span m=''2633850''>is</span> <span m=''2634080''>multiplying</span> <span m=''2634800''>the</span>
  <span m=''2634940''>ui.</span> <span m=''2635390''>Yeah,</span> <span m=''2635880''>that</span>
  <span m=''2636370''>was</span> <span m=''2638660''>[? my last i. ?]</span> </p><p><span
  m=''2640490''>OK,</span> <span m=''2640840''>this</span> <span m=''2641140''>is</span>
  <span m=''2641290''>my</span> <span m=''2641490''>matrix</span> <span m=''2646990''>from</span>
  <span m=''2647140''>odd</span> <span m=''2647390''>even</span> <span m=''2647760''>reduction.</span>
  <span m=''2649640''>It''s</span> <span m=''2649890''>just</span> <span m=''2650130''>natural</span>
  <span m=''2650530''>to</span> <span m=''2650650''>try</span> <span m=''2650970''>the</span>
  <span m=''2651110''>idea,</span> <span m=''2652620''>and</span> <span m=''2652930''>the</span>
  <span m=''2653010''>idea</span> <span m=''2653400''>works,</span> <span m=''2655300''>but</span>
  <span m=''2655570''>not</span> <span m=''2655840''>so</span> <span m=''2656790''>perfectly,</span>
  <span m=''2658540''>because</span> <span m=''2658690''>previously</span> <span m=''2660680''>in</span>
  <span m=''2660920''>1d,</span> <span m=''2662560''>that</span> <span m=''2662890''>just</span>
  <span m=''2663360''>gave</span> <span m=''2663580''>us</span> <span m=''2663710''>the</span>
  <span m=''2663810''>answer</span> <span m=''2664230''>2.</span> <span m=''2666330''>It</span>
  <span m=''2666460''>was</span> <span m=''2666650''>4</span> <span m=''2666920''>minus</span>
  <span m=''2667280''>2,</span> <span m=''2668180''>but</span> <span m=''2668400''>now</span>
  <span m=''2668640''>in 2d,</span> <span m=''2670790''>we</span> <span m=''2670950''>have</span>
  <span m=''2671130''>a</span> <span m=''2671230''>matrix,</span> <span m=''2672740''>not</span>
  <span m=''2672990''>surprising,</span> <span m=''2674150''>but</span> <span m=''2674470''>what</span>
  <span m=''2674770''>we</span> <span m=''2674960''>don''t</span> <span m=''2675230''>like</span>
  <span m=''2675590''>is</span> <span m=''2675800''>the</span> <span m=''2675940''>fact</span>
  <span m=''2676460''>that</span> <span m=''2676770''>the</span> <span m=''2676900''>bandwith</span>
  <span m=''2677530''>is</span> <span m=''2677690''>growing.</span> <span m=''2678570''>k</span>
  <span m=''2679110''>was</span> <span m=''2679390''>tri-diagonal,</span> <span m=''2680690''>but</span>
  <span m=''2680920''>when</span> <span m=''2681110''>we</span> <span m=''2681260''>square</span>
  <span m=''2681730''>it,</span> <span m=''2681890''>it</span> <span m=''2682030''>will</span>
  <span m=''2682200''>have</span> <span m=''2682420''>five</span> <span m=''2682760''>diagonal,</span>
  <span m=''2684290''>and</span> <span m=''2684550''>when</span> <span m=''2684730''>we</span>
  <span m=''2685110''>repeat</span> <span m=''2685700''>the</span> <span m=''2686450''>odd</span>
  <span m=''2686740''>even</span> <span m=''2687090''>cycles.</span> <span m=''2687770''>When</span>
  <span m=''2687920''>we</span> <span m=''2688040''>do</span> <span m=''2688240''>it</span>
  <span m=''2688360''>again.</span> <span m=''2689430''>Those</span> <span m=''2689690''>five</span>
  <span m=''2690110''>diagonals</span> <span m=''2690740''>will</span> <span m=''2690900''>be</span>
  <span m=''2691170''>nine</span> <span m=''2691550''>diagonals,</span> <span m=''2693850''>and</span>
  <span m=''2694300''>onwards.</span> <span m=''2696070''>So,</span> <span m=''2701130''>I''m</span>
  <span m=''2701340''>getting</span> <span m=''2701700''>half-sized</span> <span m=''2702450''>problems.</span>
  <span m=''2704380''>All</span> <span m=''2704740''>the</span> <span m=''2705150''>odd-numbered</span>
  <span m=''2706020''>rows</span> <span m=''2706720''>in</span> <span m=''2706950''>my</span>
  <span m=''2707440''>square</span> <span m=''2708170''>are</span> <span m=''2709360''>eliminated,</span>
  <span m=''2711400''>this</span> <span m=''2711590''>just</span> <span m=''2711840''>involves</span>
  <span m=''2712420''>the</span> <span m=''2712540''>even-numbered</span> <span m=''2713460''>rows,</span>
  <span m=''2713970''>but</span> <span m=''2714900''>the</span> <span m=''2715040''>matrix</span>
  <span m=''2715890''>is</span> <span m=''2716260''>not</span> <span m=''2718850''>tri-diagonal</span>
  <span m=''2719660''>anymore,</span> <span m=''2721500''>it''s</span> <span m=''2722010''>growing</span>
  <span m=''2723210''>in</span> <span m=''2723420''>bandwith.</span> <span m=''2724640''>So,</span>
  <span m=''2726200''>and</span> <span m=''2726500''>then</span> <span m=''2726680''>you</span>
  <span m=''2726780''>have</span> <span m=''2726970''>to</span> <span m=''2727090''>keep</span>
  <span m=''2727310''>track</span> <span m=''2727660''>of</span> <span m=''2727780''>it,</span>
  <span m=''2728480''>so</span> <span m=''2729670''>the</span> <span m=''2729920''>final</span>
  <span m=''2730290''>conclusion</span> <span m=''2730960''>is</span> <span m=''2733400''>that</span>
  <span m=''2733840''>this</span> <span m=''2734040''>is</span> <span m=''2734180''>a</span>
  <span m=''2734250''>pretty</span> <span m=''2734580''>good</span> <span m=''2734780''>idea,</span>
  <span m=''2737650''>but</span> <span m=''2738640''>it''s</span> <span m=''2738960''>not</span>
  <span m=''2739500''>quite</span> <span m=''2740000''>as</span> <span m=''2740210''>good</span>
  <span m=''2740440''>as</span> <span m=''2740570''>this</span> <span m=''2740800''>one.</span>
  <span m=''2741800''>It''s</span> <span m=''2742020''>not</span> <span m=''2742280''>as</span>
  <span m=''2742440''>good</span> <span m=''2742700''>as</span> <span m=''2743500''>the</span>
  <span m=''2743660''>FFT-based</span> <span m=''2744760''>idea.</span> </p><p><span
  m=''2745330''>Also,</span> <span m=''2746810''>if</span> <span m=''2747080''>you</span>
  <span m=''2747270''>look</span> <span m=''2747640''>to</span> <span m=''2747770''>see</span>
  <span m=''2748000''>what</span> <span m=''2748900''>is</span> <span m=''2749250''>most</span>
  <span m=''2749560''>efficient --</span> <span m=''2750230''>see the</span> <span
  m=''2750580''>eigenvectors</span> <span m=''2751380''>are</span> <span m=''2751510''>still</span>
  <span m=''2751820''>here,</span> <span m=''2752540''>so</span> <span m=''2752760''>I</span>
  <span m=''2752950''>could</span> <span m=''2753220''>do</span> <span m=''2754080''>three</span>
  <span m=''2754530''>steps</span> <span m=''2754930''>of</span> <span m=''2755100''>this</span>
  <span m=''2756420''>and</span> <span m=''2756640''>then</span> <span m=''2758310''>go</span>
  <span m=''2758470''>to</span> <span m=''2758580''>Fourier,</span> <span m=''2759690''>and</span>
  <span m=''2759890''>that</span> <span m=''2760190''>probably</span> <span m=''2760760''>is</span>
  <span m=''2760900''>about</span> <span m=''2761240''>right.</span> <span m=''2763360''>So,</span>
  <span m=''2763710''>if</span> <span m=''2763870''>you</span> <span m=''2763990''>really</span>
  <span m=''2764450''>wanted</span> <span m=''2764900''>to</span> <span m=''2765650''>polish</span>
  <span m=''2766170''>off</span> <span m=''2768010''>a</span> <span m=''2768140''>fast</span>
  <span m=''2768560''>Poisson</span> <span m=''2769100''>solver,</span> <span m=''2770340''>you</span>
  <span m=''2770600''>could</span> <span m=''2770870''>do</span> <span m=''2771740''>maybe</span>
  <span m=''2772080''>two</span> <span m=''2772280''>steps</span> <span m=''2772690''>or</span>
  <span m=''2772850''>three</span> <span m=''2773760''>of</span> <span m=''2774040''>odd</span>
  <span m=''2774290''>even</span> <span m=''2775010''>cyclic</span> <span m=''2775580''>reduction,</span>
  <span m=''2777830''>but</span> <span m=''2778040''>then</span> <span m=''2778390''>your</span>
  <span m=''2778540''>matrix</span> <span m=''2779050''>is</span> <span m=''2779270''>getting</span>
  <span m=''2779950''>messy</span> <span m=''2781200''>and</span> <span m=''2783970''>you</span>
  <span m=''2784140''>switch</span> <span m=''2784590''>to</span> <span m=''2785130''>the</span>
  <span m=''2785980''>fast</span> <span m=''2786690''>Poisson</span> <span m=''2787360''>solver,</span>
  <span m=''2787510''>so it''s</span> <span m=''2787640''>not</span> <span m=''2788460''>quite</span>
  <span m=''2788890''>Poisson</span> <span m=''2789540''>anymore,</span> <span m=''2790060''>because</span>
  <span m=''2790350''>it''s</span> <span m=''2791330''>has</span> <span m=''2791510''>a</span>
  <span m=''2791990''>messier</span> <span m=''2792420''>matrix,</span> <span m=''2792970''>but</span>
  <span m=''2793410''>it</span> <span m=''2793780''>still</span> <span m=''2795740''>has</span>
  <span m=''2796030''>the</span> <span m=''2796160''>same</span> <span m=''2796480''>eigenvectors.</span>
  <span m=''2798440''>As</span> <span m=''2798630''>long</span> <span m=''2799040''>as</span>
  <span m=''2799200''>we</span> <span m=''2799390''>stay</span> <span m=''2799880''>with</span>
  <span m=''2800080''>the</span> <span m=''2800170''>matrix</span> <span m=''2800760''>k,</span>
  <span m=''2801880''>we</span> <span m=''2802180''>know</span> <span m=''2802740''>it''s</span>
  <span m=''2802900''>eigenvectors,</span> <span m=''2804380''>and</span> <span m=''2805220''>we</span>
  <span m=''2805370''>know</span> <span m=''2805680''>that</span> <span m=''2805920''>they''re</span>
  <span m=''2807410''>sines</span> <span m=''2808410''>and</span> <span m=''2808920''>that</span>
  <span m=''2809130''>they''re</span> <span m=''2809940''>quick</span> <span m=''2810230''>to</span>
  <span m=''2810340''>work with.</span> <span m=''2811170''>OK.</span> <span m=''2812300''>Anyway,</span>
  <span m=''2812770''>there</span> <span m=''2813000''>you</span> <span m=''2813150''>go.</span>
  <span m=''2813510''>That''s</span> <span m=''2814540''>a</span> <span m=''2814680''>fast</span>
  <span m=''2815200''>algorithm</span> <span m=''2815880''>for</span> <span m=''2816220''>the</span>
  <span m=''2819360''>lecture</span> <span m=''2819690''>before</span> <span m=''2820140''>the</span>
  <span m=''2820440''>spring</span> <span m=''2820780''>break.</span> </p><p><span
  m=''2822590''>So</span> <span m=''2822740''>after</span> <span m=''2823130''>the</span>
  <span m=''2823240''>break</span> <span m=''2824030''>is,</span> <span m=''2825130''>first</span>
  <span m=''2825470''>of</span> <span m=''2825560''>all</span> <span m=''2825820''>discussion</span>
  <span m=''2826440''>of</span> <span m=''2826540''>projects.</span> <span m=''2828210''>If</span>
  <span m=''2828670''>your</span> <span m=''2828800''>project</span> <span m=''2829380''>could</span>
  <span m=''2829750''>include</span> <span m=''2832060''>page --</span> <span m=''2833070''>and</span>
  <span m=''2833260''>you</span> <span m=''2833360''>could</span> <span m=''2833630''>maybe</span>
  <span m=''2835550''>email</span> <span m=''2835930''>the</span> <span m=''2836040''>whole</span>
  <span m=''2836230''>project</span> <span m=''2836920''>to</span> <span m=''2837870''>Mr.</span>
  <span m=''2838150''>[? Cho ?].</span> <span m=''2839240''>Maybe</span> <span m=''2840510''>also,</span>
  <span m=''2840910''>could you</span> <span m=''2841140''>email</span> <span m=''2841660''>to</span>
  <span m=''2841820''>me</span> <span m=''2843070''>a</span> <span m=''2843810''>sort</span>
  <span m=''2844060''>of</span> <span m=''2845020''>summary</span> <span m=''2845460''>page</span>
  <span m=''2847100''>that</span> <span m=''2847760''>tells</span> <span m=''2848070''>me</span>
  <span m=''2848240''>what</span> <span m=''2848870''>you</span> <span m=''2849020''>did,</span>
  <span m=''2849290''>so</span> <span m=''2849420''>I''ll</span> <span m=''2849630''>save</span>
  <span m=''2850000''>the</span> <span m=''2850150''>summary</span> <span m=''2850550''>pages,</span>
  <span m=''2851040''>and</span> <span m=''2851290''>I''ll</span> <span m=''2851500''>have</span>
  <span m=''2851790''>for</span> <span m=''2852000''>Mr.</span> <span m=''2852300''>[?
  Cho ?]</span> <span m=''2852700''>the</span> <span m=''2853520''>complete</span>
  <span m=''2855180''>project</span> <span m=''2855760''>with</span> <span m=''2856950''>printout</span>
  <span m=''2857540''>and</span> <span m=''2858730''>graph,</span> <span m=''2859890''>as</span>
  <span m=''2860080''>far</span> <span m=''2860350''>as</span> <span m=''2860620''>appropriate,</span>
  <span m=''2862030''>and</span> <span m=''2862870''>so</span> <span m=''2863060''>we''ll</span>
  <span m=''2863200''>spend</span> <span m=''2863480''>some</span> <span m=''2863650''>time</span>
  <span m=''2863950''>on</span> <span m=''2864080''>that,</span> <span m=''2864490''>and</span>
  <span m=''2864740''>then</span> <span m=''2865900''>move</span> <span m=''2866410''>to</span>
  <span m=''2866550''>the</span> <span m=''2867710''>big</span> <span m=''2868000''>topic</span>
  <span m=''2868530''>of</span> <span m=''2869200''>the</span> <span m=''2872970''>rest</span>
  <span m=''2873190''>of</span> <span m=''2873250''>the</span> <span m=''2873350''>course,</span>
  <span m=''2873850''>which</span> <span m=''2874210''>is</span> <span m=''2876690''>solving</span>
  <span m=''2877970''>optimization</span> <span m=''2878910''>problems,</span> <span
  m=''2879550''>minimization,</span> <span m=''2880450''>maximization</span> <span
  m=''2883130''>in</span> <span m=''2883520''>many</span> <span m=''2883820''>variables.</span>
  <span m=''2885660''>OK,</span> <span m=''2886000''>so</span> <span m=''2886820''>have</span>
  <span m=''2887000''>a</span> <span m=''2887100''>good</span> <span m=''2887390''>spring</span>
  <span m=''2887750''>break</span> <span m=''2888240''>and</span> <span m=''2889330''>see</span>
  <span m=''2889500''>you</span> <span m=''2894430''>a</span> <span m=''2894540''>week</span>
  <span m=''2894830''>from</span> <span m=''2895010''>Wednesday.</span> <span m=''2896120''>Good.</span>
  </p>'
type: course
uid: 83635a800714eb6d074c245595d42184

---
None