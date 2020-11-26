## landrover
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## comsec
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## lego
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ollo
|expected|actual|
|--------|---|
|ollo.            86400    IN    DS    **39565** **8** 2 **63769A931A3EE95AFA940CC2D02CCDCC01BEF022B6445495AE8CB153E211B3F5**|ollo.            86400    IN    DS    **51379** **7** **1 7815633707D4A2BD28CD194B04F5B70D9A34A474**|
|a0.nic.ollo.        **172800**    IN    A    65.22.96.1|**ollo.            86400    IN    DS    51379 7 **2 **DE0BC4796BFAEBBDC19CA9A8DD731EC64E8D772292EEED0CBC71C046590DFDB9**|
|a0.nic.ollo.        **172800**    IN    AAAA    2a01:8840:5e:0:0:0:0:1|a0.nic.ollo.        **518400**    IN    A    65.22.96.1|
|a2.nic.ollo.        **172800**    IN    A    65.22.99.1|a0.nic.ollo.        **518400**    IN    AAAA    2a01:8840:5e:0:0:0:0:1|
|**a2**.nic.ollo.        **172800**    IN    AAAA    **2a01:8840:61:0:0:0:0:1**|a2.nic.ollo.        **518400**    IN    **AAAA    2a01:8840:61:0:0:0:0:1**|
|b0.nic.ollo.        **172800**    IN    A    65.22.97.1|**a2.nic.ollo.        518400    IN    **A    65.22.99.1|
|**b0**.nic.ollo.        **172800**    IN    AAAA    **2a01:8840:5f:0:0:0:0:1**|**b0**.nic.ollo.        **518400**    IN    AAAA    **2a01:8840:5f:0:0:0:0:1**|
|c0.nic.ollo.        **172800**    IN    A    65.22.98.1|b0.nic.ollo.        **518400**    IN    A    65.22.97.1|
|**c0.nic.ollo.        172800    IN    AAAA    2a01:8840:60:0:0:0:0:1**|**c0**.nic.ollo.        **518400**    IN    AAAA    **2a01:8840:60:0:0:0:0:1**|
||c0.nic.ollo.        **518400**    IN    A    65.22.98.1|
#
## vig
|expected|actual|
|--------|---|
|vig.            **86400**    IN    **DS**    **36903** **7 2 39EC8D1C662FE9C81A118705170098B0BB0ABB2F8FCCC3EA08D2E2AC6F8EDF47**|**a0.nic.**vig.        **518400**    IN    **AAAA**    **2a01:8840:2e:0:0:0:0:25**|
|a0.nic.vig.        **172800**    IN    A    65.22.48.25|a0.nic.vig.        **518400**    IN    A    65.22.48.25|
|**a0**.nic.vig.        **172800**    IN    **AAAA**    **2a01:8840:2e:0:0:0:0:25**|**a2**.nic.vig.        **518400**    IN    **A**    **65.22.51.25**|
|a2.nic.vig.        **172800**    IN    **A**    **65.22.51.25**|a2.nic.vig.        **518400**    IN    **AAAA**    **2a01:8840:31:0:0:0:0:25**|
|**a2**.nic.vig.        **172800**    IN    AAAA    **2a01:8840:31:0:0:0:0:25**|**b0**.nic.vig.        **518400**    IN    AAAA    **2a01:8840:2f:0:0:0:0:25**|
|b0.nic.vig.        **172800**    IN    A    65.22.49.25|b0.nic.vig.        **518400**    IN    A    65.22.49.25|
|**b0**.nic.vig.        **172800**    IN    AAAA    **2a01:8840:2f:0:0:0:0:25**|**c0**.nic.vig.        **518400**    IN    AAAA    **2a01:8840:30:0:0:0:0:25**|
|c0.nic.vig.        **172800**    IN    A    65.22.50.25|c0.nic.vig.        **518400**    IN    A    65.22.50.25|
|**c0.nic.vig.        172800    IN    AAAA    2a01:8840:30:0:0:0:0:25**||
#
## motorcycles
|expected|actual|
|--------|---|
|**motorcycles.        86400    IN    DS    64395 7 1 1DD446FBCE7AC93B30C0D391BD5BFFE4ED1F3552**||
|**motorcycles.        86400    IN    DS    64395 7 2 EAF5DD8ADF1BD90A49589178DF573B10B4971F34618861E546A075BB897CCD53**||
|**motorcycles.        86400    IN    DS    64740 7 2 6F78FAB74B65696CA11EBB518C0FFA7EB76114EDA9B91FC1E30D111F3A8ECC81**||
|a0.nic.motorcycles.    **172800**    IN    A    65.22.104.1|**motorcycles.        86400    IN    DS    64395 7 1 1DD446FBCE7AC93B30C0D391BD5BFFE4ED1F3552**|
|a0.nic.motorcycles.    **172800**    IN    AAAA    2a01:8840:66:0:0:0:0:1|**motorcycles.        86400    IN    DS    64395 7 2 EAF5DD8ADF1BD90A49589178DF573B10B4971F34618861E546A075BB897CCD53**|
|a2.nic.motorcycles.    **172800**    IN    **A**    **65.22.107.1**|a0.nic.motorcycles.    **518400**    IN    A    65.22.104.1|
|a2.nic.motorcycles.    **172800**    IN    **AAAA**    **2a01:8840:69:0:0:0:0:1**|a0.nic.motorcycles.    **518400**    IN    AAAA    2a01:8840:66:0:0:0:0:1|
|b0.nic.motorcycles.    **172800**    IN    A    65.22.105.1|a2.nic.motorcycles.    **518400**    IN    **AAAA**    **2a01:8840:69:0:0:0:0:1**|
|b0.nic.motorcycles.    **172800**    IN    AAAA    2a01:8840:67:0:0:0:0:1|a2.nic.motorcycles.    **518400**    IN    **A**    **65.22.107.1**|
|c0.nic.motorcycles.    **172800**    IN    A    65.22.106.1|b0.nic.motorcycles.    **518400**    IN    A    65.22.105.1|
|c0.nic.motorcycles.    **172800**    IN    AAAA    2a01:8840:68:0:0:0:0:1|b0.nic.motorcycles.    **518400**    IN    AAAA    2a01:8840:67:0:0:0:0:1|
||c0.nic.motorcycles.    **518400**    IN    A    65.22.106.1|
||c0.nic.motorcycles.    **518400**    IN    AAAA    2a01:8840:68:0:0:0:0:1|
#
## ferrari
|expected|actual|
|--------|---|
|ferrari.        86400    IN    DS    **24796** **8** 2 **33FCAB9B1F82F04CA4AD6685FAD6E660CFE968C2D0C97C08107DE4BA5C5735FA**|ferrari.        86400    IN    DS    **54001** **7** **1 FAC117F83C610585A360DAB74A942DE166CF2A91**|
|a0.nic.ferrari.        **172800**    IN    **A**    **65.22.124.25**|**ferrari.        86400    IN    DS    54001 7 **2 **B264FBFCAEA7E63C58001E081B998E7035D97E98D5B0CA34BEA76CA2B0B6ED85**|
|a0.nic.ferrari.        **172800**    IN    **AAAA**    **2a01:8840:7a:0:0:0:0:25**|a0.nic.ferrari.        **518400**    IN    **AAAA**    **2a01:8840:7a:0:0:0:0:25**|
|a2.nic.ferrari.        **172800**    IN    A    65.22.127.25|a0.nic.ferrari.        **518400**    IN    **A**    **65.22.124.25**|
|a2.nic.ferrari.        **172800**    IN    AAAA    2a01:8840:7d:0:0:0:0:25|a2.nic.ferrari.        **518400**    IN    A    65.22.127.25|
|b0.nic.ferrari.        **172800**    IN    A    65.22.125.25|a2.nic.ferrari.        **518400**    IN    AAAA    2a01:8840:7d:0:0:0:0:25|
|**b0**.nic.ferrari.        **172800**    IN    AAAA    **2a01:8840:7b:0:0:0:0:25**|b0.nic.ferrari.        **518400**    IN    **AAAA    2a01:8840:7b:0:0:0:0:25**|
|c0.nic.ferrari.        **172800**    IN    A    65.22.126.25|**b0.nic.ferrari.        518400    IN    **A    65.22.125.25|
|**c0.nic.ferrari.        172800    IN    AAAA    2a01:8840:7c:0:0:0:0:25**|**c0**.nic.ferrari.        **518400**    IN    AAAA    **2a01:8840:7c:0:0:0:0:25**|
||c0.nic.ferrari.        **518400**    IN    A    65.22.126.25|
#
## .
|expected|actual|
|--------|---|
|.            **518400**    IN    NS    a.root-servers.net.|.            **172800**    IN    NS    a.root-servers.net.|
|.            **518400**    IN    NS    b.root-servers.net.|.            **172800**    IN    NS    b.root-servers.net.|
|.            **518400**    IN    NS    c.root-servers.net.|.            **172800**    IN    NS    c.root-servers.net.|
|.            **518400**    IN    NS    d.root-servers.net.|.            **172800**    IN    NS    d.root-servers.net.|
|.            **518400**    IN    NS    e.root-servers.net.|.            **172800**    IN    NS    e.root-servers.net.|
|.            **518400**    IN    NS    f.root-servers.net.|.            **172800**    IN    NS    f.root-servers.net.|
|.            **518400**    IN    NS    g.root-servers.net.|.            **172800**    IN    NS    g.root-servers.net.|
|.            **518400**    IN    NS    h.root-servers.net.|.            **172800**    IN    NS    h.root-servers.net.|
|.            **518400**    IN    NS    i.root-servers.net.|.            **172800**    IN    NS    i.root-servers.net.|
|.            **518400**    IN    NS    j.root-servers.net.|.            **172800**    IN    NS    j.root-servers.net.|
|.            **518400**    IN    NS    k.root-servers.net.|.            **172800**    IN    NS    k.root-servers.net.|
|.            **518400**    IN    NS    l.root-servers.net.|.            **172800**    IN    NS    l.root-servers.net.|
|.            **518400**    IN    NS    m.root-servers.net.|.            **172800**    IN    NS    m.root-servers.net.|
|**.            172800    IN    DNSKEY    256 3 8 AwEAAfC/6HLClwss6h7rPfoG2cliv4/SPJRd2HPEglRsvKZRbPP2RLfiobeAkczcdqaD5q8loEt14lcTgDqwzOISZ3YvSVkM4JRMFwKzcjukKo5CsDVbMmhTD0C0yxWICRQ1M+Y5/XkZAT7mt4cb3fWcN9xgyq1wEXQX+zdLQHrNEVQSiL5SoA5cOtCSoQ45n8bKDXdw/0jjP9Rw1FVKsdzLVkQSrVMm8k30WUkHm/SK/n/954KENkdQOA6Li2vO9nicQdegyAkDeNJCdPN/p3jEhCTQLyO4AlAmyaPcDHeeo7OXr/VsYu4NTDde9hBuS0zx/rewD+BvSnmnNHNmH2FjUE8=**||
|**.            172800    IN    DNSKEY    257 3 8 AwEAAaz/tAm8yTn4Mfeh5eyI96WSVexTBAvkMgJzkKTOiW1vkIbzxeF3+/4RgWOq7HrxRixHlFlExOLAJr5emLvN7SWXgnLh4+B5xQlNVz8Og8kvArMtNROxVQuCaSnIDdD5LKyWbRd2n9WGe2R8PzgCmr3EgVLrjyBxWezF0jLHwVN8efS3rCj/EWgvIWgb9tarpVUDK/b58Da+sqqls3eNbuv7pr+eoZG+SrDK6nWeL3c6H5Apxz7LjVc1uTIdsIXxuOLYA4/ilBmSVIzuDWfdRUfhHdY6+cn8HFRm+2hM8AnXGXws9555KrUB5qihylGa8subX2Nn6UwNR1AkUTV74bU=**||
|**a.root-servers.net.    518400    IN    A    198.41.0.4**||
|**b**.root-servers.net.    518400    IN    A    199.9.14.**201**|**a**.root-servers.net.    518400    IN    A    **198.41.0.4**|
||**a.root-servers.net.    518400    IN    A    **199.9.14.**207**|
|**c**.root-servers.net.    518400    IN    A    **192**.**33**.**4**.**12**|**b**.root-servers.net.    518400    IN    A    **199**.**9**.**14**.**201**|
|**d**.root-servers.net.    518400    IN    A    **199**.**7**.**91**.**13**|**c**.root-servers.net.    518400    IN    A    **192**.**33**.**4**.**12**|
||**d.root-servers.net.    518400    IN    A    199.7.91.13**|
|**h.root-servers.net.    518400    IN    A    198.97.190.53**||
|**i**.root-servers.net.    518400    IN    A    **192**.**36**.**148**.**17**|**h**.root-servers.net.    518400    IN    A    **198**.**97**.**190**.**53**|
||**i.root-servers.net.    518400    IN    A    192.36.148.17**|
|**k.root-servers.net.    518400    IN    A    193.0.14.129**||
|**l**.root-servers.net.    518400    IN    A    **199**.**7**.**83**.**42**|**k**.root-servers.net.    518400    IN    A    **193**.**0**.**14**.**129**|
||**l.root-servers.net.    518400    IN    A    199.7.83.42**|
#
## latino
|expected|actual|
|--------|---|
|latino.            86400    IN    DS    **28831** **8** 2 **38D9082C093D8C2E653B0C2BFA3EAA463FC401FE31ED28C62B0A2B506BCF9D24**|latino.            86400    IN    DS    **53865** **7** **1 5C40427A61114B8CBBE89388D437119CE788C9CA**|
|a0.nic.latino.        **172800**    IN    **A**    **65.22.92.17**|**latino.            86400    IN    DS    53865 7 **2 **F7B3352B565C49C4ECAF7491AF0731A392E492DA71BB83E2D308C33F7371C82D**|
|a0.nic.latino.        **172800**    IN    **AAAA**    **2a01:8840:5a:0:0:0:0:17**|a0.nic.latino.        **518400**    IN    **AAAA**    **2a01:8840:5a:0:0:0:0:17**|
|a2.nic.latino.        **172800**    IN    A    65.22.95.17|a0.nic.latino.        **518400**    IN    **A**    **65.22.92.17**|
|a2.nic.latino.        **172800**    IN    AAAA    2a01:8840:5d:0:0:0:0:17|a2.nic.latino.        **518400**    IN    A    65.22.95.17|
|b0.nic.latino.        **172800**    IN    A    65.22.93.17|a2.nic.latino.        **518400**    IN    AAAA    2a01:8840:5d:0:0:0:0:17|
|b0.nic.latino.        **172800**    IN    AAAA    2a01:8840:5b:0:0:0:0:17|b0.nic.latino.        **518400**    IN    A    65.22.93.17|
|c0.nic.latino.        **172800**    IN    A    65.22.94.17|b0.nic.latino.        **518400**    IN    AAAA    2a01:8840:5b:0:0:0:0:17|
|c0.nic.latino.        **172800**    IN    AAAA    2a01:8840:5c:0:0:0:0:17|c0.nic.latino.        **518400**    IN    A    65.22.94.17|
||c0.nic.latino.        **518400**    IN    AAAA    2a01:8840:5c:0:0:0:0:17|
#
## ltda
|expected|actual|
|--------|---|
|ltda.            86400    IN    DS    **28549** **8** 2 **44371EB8133D637DE5A5F08B4465F9F92624D581808BB4547635815D455BD804**|ltda.            86400    IN    DS    **7078** **7** **1 870DC0FB8E72DF2B1079C894EA292BAC09B9318A**|
|a0.nic.ltda.        **172800**    IN    A    65.22.116.17|**ltda.            86400    IN    DS    7078 7 **2 **DE58138BDE0E73AC067CC8B976CC7FD7C5E438F5D5F6C489CA57DADA5C9146DF**|
|a0.nic.ltda.        **172800**    IN    AAAA    2a01:8840:72:0:0:0:0:17|a0.nic.ltda.        **518400**    IN    A    65.22.116.17|
|a2.nic.ltda.        **172800**    IN    A    65.22.119.17|a0.nic.ltda.        **518400**    IN    AAAA    2a01:8840:72:0:0:0:0:17|
|**a2**.nic.ltda.        **172800**    IN    AAAA    **2a01:8840:75:0:0:0:0:17**|a2.nic.ltda.        **518400**    IN    **AAAA    2a01:8840:75:0:0:0:0:17**|
|b0.nic.ltda.        **172800**    IN    A    65.22.117.17|**a2.nic.ltda.        518400    IN    **A    65.22.119.17|
|**b0.nic.ltda.        172800    IN    AAAA    2a01:8840:73:0:0:0:0:17**|**b0**.nic.ltda.        **518400**    IN    AAAA    **2a01:8840:73:0:0:0:0:17**|
|c0.nic.ltda.        **172800**    IN    A    65.22.118.17|b0.nic.ltda.        **518400**    IN    A    65.22.117.17|
|c0.nic.ltda.        **172800**    IN    AAAA    2a01:8840:74:0:0:0:0:17|c0.nic.ltda.        **518400**    IN    A    65.22.118.17|
||c0.nic.ltda.        **518400**    IN    AAAA    2a01:8840:74:0:0:0:0:17|
#
## fujixerox
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## redstone
|expected|actual|
|--------|---|
|redstone.        **86400**    IN    **DS**    **29779** **7 2 A3FC90F94A0952A7BA545A867115F6DD94B5E9ED3F86D59B6E3A32776BB5FEE0**|**a0.nic.**redstone.    **518400**    IN    **AAAA**    **2a01:8840:82:0:0:0:0:17**|
|a0.nic.redstone.    **172800**    IN    A    65.22.132.17|a0.nic.redstone.    **518400**    IN    A    65.22.132.17|
|**a0**.nic.redstone.    **172800**    IN    **AAAA**    **2a01:8840:82:0:0:0:0:17**|**a2**.nic.redstone.    **518400**    IN    **A**    **65.22.135.17**|
|a2.nic.redstone.    **172800**    IN    **A**    **65.22.135.17**|a2.nic.redstone.    **518400**    IN    **AAAA**    **2a01:8840:85:0:0:0:0:17**|
|**a2**.nic.redstone.    **172800**    IN    AAAA    **2a01:8840:85:0:0:0:0:17**|**b0**.nic.redstone.    **518400**    IN    AAAA    **2a01:8840:83:0:0:0:0:17**|
|b0.nic.redstone.    **172800**    IN    A    65.22.133.17|b0.nic.redstone.    **518400**    IN    A    65.22.133.17|
|**b0**.nic.redstone.    **172800**    IN    AAAA    **2a01:8840:83:0:0:0:0:17**|**c0**.nic.redstone.    **518400**    IN    AAAA    **2a01:8840:84:0:0:0:0:17**|
|c0.nic.redstone.    **172800**    IN    A    65.22.134.17|c0.nic.redstone.    **518400**    IN    A    65.22.134.17|
|**c0.nic.redstone.    172800    IN    AAAA    2a01:8840:84:0:0:0:0:17**||
#
## weir
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ceb
|expected|actual|
|--------|---|
|ceb.            86400    IN    DS    **26719** **8** 2 **B5E7C7283DC24CE0DFE1337A9AB5422D50F24F20C1F86AA5AE7DA2F1BA6DDA4E**|ceb.            86400    IN    DS    **40906** **7** **1 95E5C27C376408E63F94DF4A56F817CFF4B394D6**|
|a0.nic.ceb.        **172800**    IN    A    65.22.220.9|**ceb.            86400    IN    DS    40906 7 **2 **C32F435EF7DE91180784035E1B075022ED9067D0B49F10EA8DCE43E7361024F9**|
|a0.nic.ceb.        **172800**    IN    AAAA    2a01:8840:d6:0:0:0:0:9|a0.nic.ceb.        **518400**    IN    A    65.22.220.9|
|a2.nic.ceb.        **172800**    IN    A    65.22.223.9|a0.nic.ceb.        **518400**    IN    AAAA    2a01:8840:d6:0:0:0:0:9|
|a2.nic.ceb.        **172800**    IN    AAAA    2a01:8840:d9:0:0:0:0:9|a2.nic.ceb.        **518400**    IN    A    65.22.223.9|
|b0.nic.ceb.        **172800**    IN    A    65.22.221.9|a2.nic.ceb.        **518400**    IN    AAAA    2a01:8840:d9:0:0:0:0:9|
|b0.nic.ceb.        **172800**    IN    AAAA    2a01:8840:d7:0:0:0:0:9|b0.nic.ceb.        **518400**    IN    A    65.22.221.9|
|c0.nic.ceb.        **172800**    IN    **A**    **65.22.222.9**|b0.nic.ceb.        **518400**    IN    AAAA    2a01:8840:d7:0:0:0:0:9|
|c0.nic.ceb.        **172800**    IN    **AAAA**    **2a01:8840:d8:0:0:0:0:9**|c0.nic.ceb.        **518400**    IN    **AAAA**    **2a01:8840:d8:0:0:0:0:9**|
||c0.nic.ceb.        **518400**    IN    **A**    **65.22.222.9**|
#
## glade
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--b4w605ferd
|expected|actual|
|--------|---|
|xn--b4w605ferd.        86400    IN    DS    **56659** **8** 2 **BD5E5982605E7EC6077B7742D7894A6959657AFBFE9EE345EDA682A9A4BF0252**|xn--b4w605ferd.        86400    IN    DS    **16669** **7** **1 2DC5701A45EF3BEB7A84AEFAF6DBD3B4145F56E3**|
|a0.nic.xn--b4w605ferd.    **172800**    IN    A    65.22.140.1|**xn--b4w605ferd.        86400    IN    DS    16669 7 **2 **BD4C6BCAABDE7A16DF54E658C57955802BF98AD2EB5F2BA696FA66495825C740**|
|a0.nic.xn--b4w605ferd.    **172800**    IN    AAAA    2a01:8840:8a:0:0:0:0:1|a0.nic.xn--b4w605ferd.    **518400**    IN    A    65.22.140.1|
|a2.nic.xn--b4w605ferd.    **172800**    IN    **A**    **65.22.143.1**|a0.nic.xn--b4w605ferd.    **518400**    IN    AAAA    2a01:8840:8a:0:0:0:0:1|
|a2.nic.xn--b4w605ferd.    **172800**    IN    **AAAA**    **2a01:8840:8d:0:0:0:0:1**|a2.nic.xn--b4w605ferd.    **518400**    IN    **AAAA**    **2a01:8840:8d:0:0:0:0:1**|
|b0.nic.xn--b4w605ferd.    **172800**    IN    A    65.22.141.1|a2.nic.xn--b4w605ferd.    **518400**    IN    **A**    **65.22.143.1**|
|b0.nic.xn--b4w605ferd.    **172800**    IN    AAAA    2a01:8840:8b:0:0:0:0:1|b0.nic.xn--b4w605ferd.    **518400**    IN    A    65.22.141.1|
|c0.nic.xn--b4w605ferd.    **172800**    IN    **A**    **65.22.142.1**|b0.nic.xn--b4w605ferd.    **518400**    IN    AAAA    2a01:8840:8b:0:0:0:0:1|
|c0.nic.xn--b4w605ferd.    **172800**    IN    **AAAA**    **2a01:8840:8c:0:0:0:0:1**|c0.nic.xn--b4w605ferd.    **518400**    IN    **AAAA**    **2a01:8840:8c:0:0:0:0:1**|
||c0.nic.xn--b4w605ferd.    **518400**    IN    **A**    **65.22.142.1**|
#
## cfa
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## abb
|expected|actual|
|--------|---|
||**abb.            172800    IN    NS    ns.uat.com.**|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA    2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    A    192.42.176.30|**ac4.nstld.com.        518400    IN    **A    192.42.176.30|
|**ac4**.**nstld**.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|**ns**.**uat**.com.        **518400**    IN    **A**    **192.42.170.30**|
#
## cfd
|expected|actual|
|--------|---|
|cfd.            172800    IN    NS    **a**.**nic**.**cfd**.|cfd.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|cfd.            172800    IN    NS    **b**.**nic**.**cfd**.|cfd.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|cfd.            172800    IN    NS    **c**.**nic**.**cfd**.|cfd.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|cfd.            172800    IN    NS    **d**.**nic**.**cfd**.|cfd.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**cfd.            86400    IN    DS    10525 8 2 42FD41D6533AC785EF64CF9BD36B16463C5A161DA2AF25EC08C114B40E82F2D8**||
|**a**.**nic**.**cfd**.        **172800**    IN    A    **194**.**169**.**218**.**122**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**cfd**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:122**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**b.nic.cfd.        172800    IN    **A    **185**.**24**.**64**.**122**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b**.**nic**.**cfd**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:122**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**c**.**nic**.**cfd**.        **172800**    IN    A    **212**.**18**.**248**.**122**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**cfd**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:122**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**d**.**nic**.**cfd**.        **172800**    IN    **A**    **212.18.249.122**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**cfd**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:122**||
#
## website
|expected|actual|
|--------|---|
|website.        172800    IN    NS    **e**.nic.website.|website.        172800    IN    NS    **c**.nic.website.|
|website.        172800    IN    NS    **f**.nic.website.|website.        172800    IN    NS    **d**.nic.website.|
|a.nic.website.        **172800**    IN    **A**    **194.169.218.52**|a.nic.website.        **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:52**|
|a.nic.website.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:52**|a.nic.website.        **518400**    IN    **A**    **194.169.218.52**|
|b.nic.website.        **172800**    IN    A    185.24.64.52|b.nic.website.        **518400**    IN    A    185.24.64.52|
|b.nic.website.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:52|b.nic.website.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:52|
|**e**.nic.website.        **172800**    IN    A    **212**.**18**.**248**.**52**|**c**.nic.website.        **518400**    IN    A    **185**.**38**.**99**.**1**|
|**e**.nic.website.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:52**|**c**.nic.website.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:1**|
|**f**.nic.website.        **172800**    IN    A    **212**.**18**.**249**.**52**|**d**.nic.website.        **518400**    IN    A    **108**.**59**.**161**.**1**|
|**f**.nic.website.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:52**|**d**.nic.website.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:1**|
#
## abc
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--c2br7g
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--11b4c3d
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sling
|expected|actual|
|--------|---|
|sling.            86400    IN    DS    **46550** **8** **2** **FC817BC7BCC7EDCC930CF73483FDE9A88386E85674D7CF438E36ED5D00CDF74F**|sling.            86400    IN    DS    **1935** **7** **1** **58A4213E236FCE58F6772240DB43A63E61FE6801**|
|**a0.nic.**sling.        **172800**    IN    **A**    **65.22.108.9**|sling.            **86400**    IN    **DS**    **1935** **7 2 7FAFDDB40A8428C6AE8EB6C473AAE6A695443A6E6059B4F2F78F1EF8E471F48C**|
|a0.nic.sling.        **172800**    IN    AAAA    2a01:8840:6a:0:0:0:0:9|a0.nic.sling.        **518400**    IN    AAAA    2a01:8840:6a:0:0:0:0:9|
|**a2**.nic.sling.        **172800**    IN    A    65.22.**111**.9|**a0**.nic.sling.        **518400**    IN    A    65.22.**108**.9|
|a2.nic.sling.        **172800**    IN    AAAA    2a01:8840:6d:0:0:0:0:9|a2.nic.sling.        **518400**    IN    AAAA    2a01:8840:6d:0:0:0:0:9|
|**b0**.nic.sling.        **172800**    IN    A    65.22.**109**.9|**a2**.nic.sling.        **518400**    IN    A    65.22.**111**.9|
|b0.nic.sling.        **172800**    IN    AAAA    2a01:8840:6b:0:0:0:0:9|b0.nic.sling.        **518400**    IN    AAAA    2a01:8840:6b:0:0:0:0:9|
|c0.nic.sling.        **172800**    IN    A    65.22.110.9|**b0.nic.sling.        518400    IN    A    65.22.109.9**|
|c0.nic.sling.        **172800**    IN    AAAA    2a01:8840:6c:0:0:0:0:9|c0.nic.sling.        **518400**    IN    A    65.22.110.9|
||c0.nic.sling.        **518400**    IN    AAAA    2a01:8840:6c:0:0:0:0:9|
#
## thd
|expected|actual|
|--------|---|
|thd.            86400    IN    DS    **16237** **8** 2 **A2B1E70EC2A5831A069B94CCF9B39E547CD9A351055EA87F4B74DD99F7B061E1**|thd.            86400    IN    DS    **43611** **7** **1 99F684F067434A0DF49F283603446367EA4F1144**|
|a0.nic.thd.        **172800**    IN    A    65.22.192.9|**thd.            86400    IN    DS    43611 7 **2 **C4491DC711EBF4A5DAF174EE62AA034B144E9EA1533F1A86284BA44510A3A8BE**|
|a0.nic.thd.        **172800**    IN    AAAA    2a01:8840:ba:0:0:0:0:9|a0.nic.thd.        **518400**    IN    A    65.22.192.9|
|a2.nic.thd.        **172800**    IN    A    65.22.195.9|a0.nic.thd.        **518400**    IN    AAAA    2a01:8840:ba:0:0:0:0:9|
|a2.nic.thd.        **172800**    IN    AAAA    2a01:8840:bd:0:0:0:0:9|a2.nic.thd.        **518400**    IN    A    65.22.195.9|
|b0.nic.thd.        **172800**    IN    **A**    **65.22.193.9**|a2.nic.thd.        **518400**    IN    AAAA    2a01:8840:bd:0:0:0:0:9|
|b0.nic.thd.        **172800**    IN    **AAAA**    **2a01:8840:bb:0:0:0:0:9**|b0.nic.thd.        **518400**    IN    **AAAA**    **2a01:8840:bb:0:0:0:0:9**|
|c0.nic.thd.        **172800**    IN    A    65.22.194.9|b0.nic.thd.        **518400**    IN    **A**    **65.22.193.9**|
|c0.nic.thd.        **172800**    IN    AAAA    2a01:8840:bc:0:0:0:0:9|c0.nic.thd.        **518400**    IN    A    65.22.194.9|
||c0.nic.thd.        **518400**    IN    AAAA    2a01:8840:bc:0:0:0:0:9|
#
## spreadbetting
|expected|actual|
|--------|---|
|spreadbetting.        172800    IN    NS    **a**.**nic**.**spreadbetting**.|spreadbetting.        172800    IN    NS    **ac1**.**nstld**.**com**.|
|spreadbetting.        172800    IN    NS    **b**.**nic**.**spreadbetting**.|spreadbetting.        172800    IN    NS    **ac2**.**nstld**.**com**.|
|spreadbetting.        172800    IN    NS    **c**.**nic**.**spreadbetting**.|spreadbetting.        172800    IN    NS    **ac3**.**nstld**.**com**.|
|spreadbetting.        172800    IN    NS    **d**.**nic**.**spreadbetting**.|spreadbetting.        172800    IN    NS    **ac4**.**nstld**.**com**.|
|**spreadbetting.        86400    IN    DS    41200 8 2 41681390105222B0E91FED4A6EA44F88685DD9756A3FD632FD0E23C04B084E01**||
|**a**.**nic**.**spreadbetting**.    **172800**    IN    A    **194**.**169**.**218**.**124**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**spreadbetting**.    **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:124**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**b.nic.spreadbetting.    172800    IN    **A    **185**.**24**.**64**.**124**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b**.**nic**.**spreadbetting**.    **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:124**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**c**.**nic**.**spreadbetting**.    **172800**    IN    A    **212**.**18**.**248**.**124**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**spreadbetting**.    **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:124**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**d**.**nic**.**spreadbetting**.    **172800**    IN    **A**    **212.18.249.124**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**spreadbetting**.    **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:124**||
#
## blue
|expected|actual|
|--------|---|
|**blue.            172800    IN    NS    b2.nic.blue.**||
|blue.            86400    IN    DS    **13015** **8** 2 **337188914037F0D7831C5C732516D7310C1D291F55ECFE67CD8B9F4CED0B706A**|blue.            86400    IN    DS    **26950** **7** **1 A6DE389755ABBAF7B58547B03F0D46E3C210687B**|
|a0.nic.blue.        **172800**    IN    **A**    **65.22.28.9**|**blue.            86400    IN    DS    26950 7 **2 **AECA57D8557C1F9F486AD18216FAE2DA2E8539E6F157DBF876BA6DF1FEE1604D**|
|a0.nic.blue.        **172800**    IN    **AAAA**    **2a01:8840:1e:0:0:0:0:9**|a0.nic.blue.        **518400**    IN    **AAAA**    **2a01:8840:1e:0:0:0:0:9**|
|a2.nic.blue.        **172800**    IN    A    65.22.31.9|a0.nic.blue.        **518400**    IN    **A**    **65.22.28.9**|
|a2.nic.blue.        **172800**    IN    AAAA    2a01:8840:21:0:0:0:0:9|a2.nic.blue.        **518400**    IN    A    65.22.31.9|
|b0.nic.blue.        **172800**    IN    A    65.22.29.9|a2.nic.blue.        **518400**    IN    AAAA    2a01:8840:21:0:0:0:0:9|
|b0.nic.blue.        **172800**    IN    AAAA    2a01:8840:1f:0:0:0:0:9|b0.nic.blue.        **518400**    IN    A    65.22.29.9|
|**b2**.nic.blue.        **172800**    IN    **A    65.22.31.13**|b0.nic.blue.        **518400**    IN    AAAA    2a01:8840:1f:0:0:0:0:9|
|**b2.nic.blue.        172800    IN    **AAAA    **2a01:8840:21:0:0:0:0:13**|**c0**.nic.blue.        **518400**    IN    AAAA    **2a01:8840:20:0:0:0:0:9**|
|c0.nic.blue.        **172800**    IN    A    65.22.30.9|c0.nic.blue.        **518400**    IN    A    65.22.30.9|
|**c0.nic.blue.        172800    IN    AAAA    2a01:8840:20:0:0:0:0:9**||
#
## ericsson
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## grocery
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## volvo
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ist
|expected|actual|
|--------|---|
|ist.            86400    IN    DS    **2221** **8** 2 **7F26778AFF98DAD019476832C62CE0399F247BA6F4F8E10BF26B8C80DB6E30D9**|ist.            86400    IN    DS    **64746** **7** **1 C73CC6FFC540BB0F6FEE745CA78A6C9A6E6AA436**|
|a0.nic.ist.        **172800**    IN    **A**    **65.22.144.1**|**ist.            86400    IN    DS    64746 7 **2 **AD2C997EC6DE185C9396EC62DC249984BE7BCFB8250AFF7EA1294CE1045A0536**|
|a0.nic.ist.        **172800**    IN    **AAAA**    **2a01:8840:8e:0:0:0:0:1**|a0.nic.ist.        **518400**    IN    **AAAA**    **2a01:8840:8e:0:0:0:0:1**|
|a2.nic.ist.        **172800**    IN    A    65.22.147.1|a0.nic.ist.        **518400**    IN    **A**    **65.22.144.1**|
|a2.nic.ist.        **172800**    IN    AAAA    2a01:8840:91:0:0:0:0:1|a2.nic.ist.        **518400**    IN    A    65.22.147.1|
|b0.nic.ist.        **172800**    IN    A    65.22.145.1|a2.nic.ist.        **518400**    IN    AAAA    2a01:8840:91:0:0:0:0:1|
|**b0**.nic.ist.        **172800**    IN    AAAA    **2a01:8840:8f:0:0:0:0:1**|b0.nic.ist.        **518400**    IN    **AAAA    2a01:8840:8f:0:0:0:0:1**|
|c0.nic.ist.        **172800**    IN    A    65.22.146.1|**b0.nic.ist.        518400    IN    **A    65.22.145.1|
|**c0.nic.ist.        172800    IN    AAAA    2a01:8840:90:0:0:0:0:1**|**c0**.nic.ist.        **518400**    IN    AAAA    **2a01:8840:90:0:0:0:0:1**|
||c0.nic.ist.        **518400**    IN    A    65.22.146.1|
#
## aco
|expected|actual|
|--------|---|
|aco.            172800    IN    NS    **a**.**dns.**nic.aco.|aco.            172800    IN    NS    **a0**.nic.aco.|
|aco.            172800    IN    NS    **m**.**dns.**nic.aco.|aco.            172800    IN    NS    **a2**.nic.aco.|
|aco.            172800    IN    NS    **n**.**dns**.nic.aco.|aco.            172800    IN    NS    **b0**.**nic**.**aco.**|
|aco.            86400    IN    DS    **14236** 7 1 **4C5878A7C0583C483D77F8CC45A2B1A10F970C2B**|**aco.            172800    IN    NS    c0.**nic.aco.|
|aco.            86400    IN    DS    **14236** 7 2 **EBE522B5FD92401588E751D55569D10536E02834E54435C0A9C8ED7476D2744F**|aco.            86400    IN    DS    **49383** 7 1 **C536914CD2ECC3A45F2BCA3279FD1A25062156B1**|
|aco.            **86400**    IN    **DS**    **37419** **7 2 FB6894A0AC51D59FDAE1F639D3617F974509D5B37A10279695517D7A960104F4**|aco.            86400    IN    DS    **49383** 7 2 **871A9DDD4FEEF3531929E3866BFCAF8E97E7FE0688D14EF897F1AFCC1CD58F60**|
|**a**.**dns.**nic.aco.        **172800**    IN    A    **194**.**0**.**25**.**32**|**a0.nic.**aco.        **518400**    IN    **AAAA**    **2a01:8840:8e:0:0:0:0:17**|
|**a**.**dns.**nic.aco.        **172800**    IN    **AAAA**    **2001:678:20:0:0:0:0:32**|**a0**.nic.aco.        **518400**    IN    A    **65**.**22**.**144**.**17**|
|**m**.**dns**.nic.aco.        **172800**    IN    **A**    **194.0.26.12**|**a2**.nic.aco.        **518400**    IN    **A**    **65**.**22**.**147.17**|
|**m**.**dns.**nic.aco.        **172800**    IN    AAAA    **2001:67c:10e0:0:0:0:0:12**|**a2.**nic.aco.        **518400**    IN    **AAAA**    **2a01:8840:91:0:0:0:0:17**|
|**n**.**dns.**nic.aco.        **172800**    IN    A    **194**.**0**.**24**.**12**|**b0**.nic.aco.        **518400**    IN    AAAA    **2a01:8840:8f:0:0:0:0:17**|
|**n**.**dns.**nic.aco.        **172800**    IN    AAAA    **2001:678:24:0:0:0:0:12**|**b0**.nic.aco.        **518400**    IN    A    **65**.**22**.**145**.**17**|
||**c0**.nic.aco.        **518400**    IN    AAAA    **2a01:8840:90:0:0:0:0:17**|
||**c0.nic.aco.        518400    IN    A    65.22.146.17**|
#
## red
|expected|actual|
|--------|---|
|red.            86400    IN    DS    **20191** **8** 2 **A838978F76DAB8C9A0057B3FDDDBD9883E760764E5AE1CEA04F0961D61A4BB28**|red.            86400    IN    DS    **20431** **7** **1 429A68CBBF8ACE08D911071D13FD47892B1EFEF7**|
|a0.nic.red.        **172800**    IN    **A**    **65.22.36.25**|**red.            86400    IN    DS    20431 7 **2 **7ED8016E603F6E4B0AEBDA756B01AAE19AE9C65D9A8DA32C1FD1CC74BCE999F4**|
|a0.nic.red.        **172800**    IN    **AAAA**    **2a01:8840:26:0:0:0:0:25**|a0.nic.red.        **518400**    IN    **AAAA**    **2a01:8840:26:0:0:0:0:25**|
|a2.nic.red.        **172800**    IN    A    65.22.39.25|a0.nic.red.        **518400**    IN    **A**    **65.22.36.25**|
|a2.nic.red.        **172800**    IN    AAAA    2a01:8840:29:0:0:0:0:25|a2.nic.red.        **518400**    IN    A    65.22.39.25|
|b0.nic.red.        **172800**    IN    **A**    **65.22.37.25**|a2.nic.red.        **518400**    IN    AAAA    2a01:8840:29:0:0:0:0:25|
|b0.nic.red.        **172800**    IN    **AAAA**    **2a01:8840:27:0:0:0:0:25**|b0.nic.red.        **518400**    IN    **AAAA**    **2a01:8840:27:0:0:0:0:25**|
|c0.nic.red.        **172800**    IN    A    65.22.38.25|b0.nic.red.        **518400**    IN    **A**    **65.22.37.25**|
|c0.nic.red.        **172800**    IN    AAAA    2a01:8840:28:0:0:0:0:25|c0.nic.red.        **518400**    IN    A    65.22.38.25|
||c0.nic.red.        **518400**    IN    AAAA    2a01:8840:28:0:0:0:0:25|
#
## avianca
|expected|actual|
|--------|---|
|avianca.        **86400**    IN    **DS**    **42183** **7 2 0AB85E2FAD8AEBCC500B29CF5E9EC6AADC96BBA5424118BFEE9342C2C52900FC**|**a0.nic.**avianca.        **518400**    IN    **AAAA**    **2a01:8840:4e:0:0:0:0:17**|
|a0.nic.avianca.        **172800**    IN    A    65.22.80.17|a0.nic.avianca.        **518400**    IN    A    65.22.80.17|
|**a0.nic.avianca.        172800    IN    AAAA    2a01:8840:4e:0:0:0:0:17**|a2.nic.avianca.        **518400**    IN    A    65.22.83.17|
|a2.nic.avianca.        **172800**    IN    A    65.22.83.17|a2.nic.avianca.        **518400**    IN    AAAA    2a01:8840:51:0:0:0:0:17|
|a2.nic.avianca.        **172800**    IN    AAAA    2a01:8840:51:0:0:0:0:17|b0.nic.avianca.        **518400**    IN    **AAAA**    **2a01:8840:4f:0:0:0:0:17**|
|b0.nic.avianca.        **172800**    IN    **A**    **65.22.81.17**|b0.nic.avianca.        **518400**    IN    **A**    **65.22.81.17**|
|b0.nic.avianca.        **172800**    IN    **AAAA**    **2a01:8840:4f:0:0:0:0:17**|c0.nic.avianca.        **518400**    IN    A    65.22.82.17|
|c0.nic.avianca.        **172800**    IN    A    65.22.82.17|c0.nic.avianca.        **518400**    IN    AAAA    2a01:8840:50:0:0:0:0:17|
|c0.nic.avianca.        **172800**    IN    AAAA    2a01:8840:50:0:0:0:0:17||
#
## post
|expected|actual|
|--------|---|
|**post.            86400    IN    DS    61395 7 2 E508F17C1EEA06F353CC7A119E8822915A66143D8E22A2F9DF5FE891861E35CA**|a0.post.afilias-nst.info.    **518400**    IN    A    65.22.0.1|
|a0.post.afilias-nst.info.    **172800**    IN    A    65.22.0.1|a0.post.afilias-nst.info.    **518400**    IN    AAAA    2a01:8840:0:0:0:0:0:1|
|a0.post.afilias-nst.info.    **172800**    IN    AAAA    2a01:8840:0:0:0:0:0:1|a2.post.afilias-nst.info.    **518400**    IN    **AAAA    2a01:8840:4:0:0:0:0:1**|
|a2.post.afilias-nst.info.    **172800**    IN    A    65.22.4.1|**a2.post.afilias-nst.info.    518400    IN    **A    65.22.4.1|
|**a2**.post.afilias-nst.info.    **172800**    IN    AAAA    **2a01:8840:4:0:0:0:0:1**|**c0**.post.afilias-nst.info.    **518400**    IN    AAAA    **2a01:8840:2:0:0:0:0:1**|
|c0.post.afilias-nst.info.    **172800**    IN    A    65.22.2.1|c0.post.afilias-nst.info.    **518400**    IN    A    65.22.2.1|
|**c0.post.afilias-nst.info.    172800    IN    AAAA    2a01:8840:2:0:0:0:0:1**|b0.post.afilias-nst.org.    **518400**    IN    A    65.22.1.1|
|b0.post.afilias-nst.org.    **172800**    IN    A    65.22.1.1|b0.post.afilias-nst.org.    **518400**    IN    AAAA    2a01:8840:1:0:0:0:0:1|
|b0.post.afilias-nst.org.    **172800**    IN    AAAA    2a01:8840:1:0:0:0:0:1|b2.post.afilias-nst.org.    **518400**    IN    **AAAA**    **2a01:8840:5:0:0:0:0:1**|
|b2.post.afilias-nst.org.    **172800**    IN    **A**    **65.22.5.1**|b2.post.afilias-nst.org.    **518400**    IN    **A**    **65.22.5.1**|
|b2.post.afilias-nst.org.    **172800**    IN    **AAAA**    **2a01:8840:5:0:0:0:0:1**|d0.post.afilias-nst.org.    **518400**    IN    A    65.22.3.1|
|d0.post.afilias-nst.org.    **172800**    IN    A    65.22.3.1|d0.post.afilias-nst.org.    **518400**    IN    AAAA    2a01:8840:3:0:0:0:0:1|
|d0.post.afilias-nst.org.    **172800**    IN    AAAA    2a01:8840:3:0:0:0:0:1||
#
## duck
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ren
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## bostik
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## clinique
|expected|actual|
|--------|---|
|clinique.        86400    IN    DS    **51286** **8** **2** **2456B103E69D9F788B97912B8DFBA0FBFDF574ABFA166DDD1C773DCF252B3BDE**|clinique.        86400    IN    DS    **62341** **7** **1** **DC2C1A2539146A03A2D989B6487FD2C3319954AC**|
|**a0.nic.**clinique.    **172800**    IN    **A**    **65.22.52.41**|clinique.        **86400**    IN    **DS**    **62341** **7 2 ECEB8CF9F7C2B915AB5A3C4D929960E9DB21BE3F0CD48EC489324C53314EA338**|
|a0.nic.clinique.    **172800**    IN    AAAA    2a01:8840:32:0:0:0:0:41|a0.nic.clinique.    **518400**    IN    AAAA    2a01:8840:32:0:0:0:0:41|
|**a2**.nic.clinique.    **172800**    IN    A    65.22.**55**.41|**a0**.nic.clinique.    **518400**    IN    A    65.22.**52**.41|
|a2.nic.clinique.    **172800**    IN    AAAA    2a01:8840:35:0:0:0:0:41|a2.nic.clinique.    **518400**    IN    AAAA    2a01:8840:35:0:0:0:0:41|
|**b0**.nic.clinique.    **172800**    IN    A    65.22.**53**.41|**a2**.nic.clinique.    **518400**    IN    A    65.22.**55**.41|
|b0.nic.clinique.    **172800**    IN    AAAA    2a01:8840:33:0:0:0:0:41|b0.nic.clinique.    **518400**    IN    AAAA    2a01:8840:33:0:0:0:0:41|
|c0.nic.clinique.    **172800**    IN    AAAA    2a01:8840:34:0:0:0:0:41|**b0.nic.clinique.    518400    IN    A    65.22.53.41**|
|c0.nic.clinique.    **172800**    IN    A    65.22.54.41|c0.nic.clinique.    **518400**    IN    AAAA    2a01:8840:34:0:0:0:0:41|
||c0.nic.clinique.    **518400**    IN    A    65.22.54.41|
#
## itv
|expected|actual|
|--------|---|
|itv.            86400    IN    DS    **47554** **8** **2** **B40BD9C46F4EA1A9A496C57C37A91938AF59778971851D7D91C54DC203649C13**|itv.            86400    IN    DS    **30558** **7** **1** **44A43507E232590DCCABEE9BB4BC5617D37E1694**|
|**a0.nic.**itv.        **172800**    IN    **A**    **65.22.88.25**|itv.            **86400**    IN    **DS**    **30558** **7 2 A675A7B443E3D3F78C1110CA7E37C007EB1913B81009F0B8520E2FA12D2CDB49**|
|a0.nic.itv.        **172800**    IN    AAAA    2a01:8840:56:0:0:0:0:25|a0.nic.itv.        **518400**    IN    AAAA    2a01:8840:56:0:0:0:0:25|
|**a2**.nic.itv.        **172800**    IN    A    65.22.**91**.25|**a0**.nic.itv.        **518400**    IN    A    65.22.**88**.25|
|a2.nic.itv.        **172800**    IN    AAAA    2a01:8840:59:0:0:0:0:25|a2.nic.itv.        **518400**    IN    AAAA    2a01:8840:59:0:0:0:0:25|
|**b0**.nic.itv.        **172800**    IN    A    65.22.**89**.25|**a2**.nic.itv.        **518400**    IN    A    65.22.**91**.25|
|b0.nic.itv.        **172800**    IN    AAAA    2a01:8840:57:0:0:0:0:25|b0.nic.itv.        **518400**    IN    AAAA    2a01:8840:57:0:0:0:0:25|
|c0.nic.itv.        **172800**    IN    A    65.22.90.25|**b0.nic.itv.        518400    IN    A    65.22.89.25**|
|c0.nic.itv.        **172800**    IN    AAAA    2a01:8840:58:0:0:0:0:25|c0.nic.itv.        **518400**    IN    A    65.22.90.25|
||c0.nic.itv.        **518400**    IN    AAAA    2a01:8840:58:0:0:0:0:25|
#
## lasalle
|expected|actual|
|--------|---|
|lasalle.        86400    IN    DS    **6184** **8** 2 **B7CEB81D5279786BE446C8D6981F911D3CB31DFC7E192DE510C6D489CA3BA370**|lasalle.        86400    IN    DS    **25206** **7** **1 B5F7EE824DF381D671690718977488D0756EF665**|
|a0.nic.lasalle.        **172800**    IN    A    65.22.148.1|**lasalle.        86400    IN    DS    25206 7 **2 **A5DFDC18F4CCFB1BD8D4AC1C88C1C4864795DC7A1BE2C22D11E0D473B25C2462**|
|a0.nic.lasalle.        **172800**    IN    AAAA    2a01:8840:92:0:0:0:0:1|a0.nic.lasalle.        **518400**    IN    A    65.22.148.1|
|a2.nic.lasalle.        **172800**    IN    A    65.22.151.1|a0.nic.lasalle.        **518400**    IN    AAAA    2a01:8840:92:0:0:0:0:1|
|a2.nic.lasalle.        **172800**    IN    AAAA    2a01:8840:95:0:0:0:0:1|a2.nic.lasalle.        **518400**    IN    A    65.22.151.1|
|b0.nic.lasalle.        **172800**    IN    A    65.22.149.1|a2.nic.lasalle.        **518400**    IN    AAAA    2a01:8840:95:0:0:0:0:1|
|b0.nic.lasalle.        **172800**    IN    AAAA    2a01:8840:93:0:0:0:0:1|b0.nic.lasalle.        **518400**    IN    A    65.22.149.1|
|c0.nic.lasalle.        **172800**    IN    **A**    **65.22.150.1**|b0.nic.lasalle.        **518400**    IN    AAAA    2a01:8840:93:0:0:0:0:1|
|c0.nic.lasalle.        **172800**    IN    **AAAA**    **2a01:8840:94:0:0:0:0:1**|c0.nic.lasalle.        **518400**    IN    **AAAA**    **2a01:8840:94:0:0:0:0:1**|
||c0.nic.lasalle.        **518400**    IN    **A**    **65.22.150.1**|
#
## shell
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## alfaromeo
|expected|actual|
|--------|---|
|alfaromeo.        86400    IN    DS    **61387** **8** 2 **64C23C01756936C2C088966C6540FC74E30E194D2C874DDB24E99D0E4BC58F96**|alfaromeo.        86400    IN    DS    **44769** **7** **1 04AAB9DE5D239F493B55531013269B368B9C72F0**|
|a0.nic.alfaromeo.    **172800**    IN    A    65.22.124.17|**alfaromeo.        86400    IN    DS    44769 7 **2 **D05E811B7B466B5EC91565EA1306158F482449351D99734814B89F1C765EC2FC**|
|a0.nic.alfaromeo.    **172800**    IN    AAAA    2a01:8840:7a:0:0:0:0:17|a0.nic.alfaromeo.    **518400**    IN    A    65.22.124.17|
|a2.nic.alfaromeo.    **172800**    IN    A    65.22.127.17|a0.nic.alfaromeo.    **518400**    IN    AAAA    2a01:8840:7a:0:0:0:0:17|
|a2.nic.alfaromeo.    **172800**    IN    AAAA    2a01:8840:7d:0:0:0:0:17|a2.nic.alfaromeo.    **518400**    IN    A    65.22.127.17|
|b0.nic.alfaromeo.    **172800**    IN    **A**    **65.22.125.17**|a2.nic.alfaromeo.    **518400**    IN    AAAA    2a01:8840:7d:0:0:0:0:17|
|b0.nic.alfaromeo.    **172800**    IN    **AAAA**    **2a01:8840:7b:0:0:0:0:17**|b0.nic.alfaromeo.    **518400**    IN    **AAAA**    **2a01:8840:7b:0:0:0:0:17**|
|c0.nic.alfaromeo.    **172800**    IN    A    65.22.126.17|b0.nic.alfaromeo.    **518400**    IN    **A**    **65.22.125.17**|
|c0.nic.alfaromeo.    **172800**    IN    AAAA    2a01:8840:7c:0:0:0:0:17|c0.nic.alfaromeo.    **518400**    IN    A    65.22.126.17|
||c0.nic.alfaromeo.    **518400**    IN    AAAA    2a01:8840:7c:0:0:0:0:17|
#
## trust
|expected|actual|
|--------|---|
|**trust.            86400    IN    DS    65044 8 1 5D9DE840AB80B8FC0269EEEB33D97C8BEB9B81A5**|a.nic.trust.        **518400**    IN    A    37.209.192.10|
|**trust.            86400    IN    DS    65044 8 2 E3999245A03C4331FB3961D350AD85744EBF2002738CBB433AD0B863FBDAEF1C**|a.nic.trust.        **518400**    IN    AAAA    2001:dcd:1:0:0:0:0:10|
|a.nic.trust.        **172800**    IN    A    37.209.192.10|b.nic.trust.        **518400**    IN    **AAAA    2001:dcd:2:0:0:0:0:10**|
|a.nic.trust.        **172800**    IN    AAAA    2001:dcd:1:0:0:0:0:10|**b.nic.trust.        518400    IN    **A    37.209.194.10|
|b.nic.trust.        **172800**    IN    A    37.209.194.10|**c**.nic.trust.        **518400**    IN    AAAA    **2001:dcd:3:0:0:0:0:10**|
|**b**.nic.trust.        **172800**    IN    AAAA    **2001:dcd:2:0:0:0:0:10**|c.nic.trust.        **518400**    IN    A    37.209.196.10|
|c.nic.trust.        **172800**    IN    A    37.209.196.10|**d**.nic.trust.        **518400**    IN    AAAA    **2001:dcd:4:0:0:0:0:10**|
|**c**.nic.trust.        **172800**    IN    AAAA    **2001:dcd:3:0:0:0:0:10**|d.nic.trust.        **518400**    IN    A    37.209.198.10|
|d.nic.trust.        **172800**    IN    A    37.209.198.10||
|**d.nic.trust.        172800    IN    AAAA    2001:dcd:4:0:0:0:0:10**||
#
## aeg
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## samsung
|expected|actual|
|--------|---|
||**samsung.        172800    IN    NS    a.samsung.dyntld.net.**|
||**samsung.        172800    IN    NS    b.samsung.dyntld.net.**|
||**samsung.        172800    IN    NS    c.samsung.dyntld.net.**|
||**samsung.        172800    IN    NS    d.samsung.dyntld.net.**|
|ns1.samsung.centralnic-dns.com.    **172800**    IN    A    194.169.218.112|ns1.samsung.centralnic-dns.com.    **518400**    IN    A    194.169.218.112|
|ns1.samsung.centralnic-dns.com.    **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:112|ns1.samsung.centralnic-dns.com.    **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:112|
|ns2.samsung.centralnic-dns.com.    **172800**    IN    A    185.24.64.112|ns2.samsung.centralnic-dns.com.    **518400**    IN    A    185.24.64.112|
|ns2.samsung.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:112|ns2.samsung.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:112|
|ns3.samsung.centralnic-dns.com.    **172800**    IN    A    212.18.248.112|ns3.samsung.centralnic-dns.com.    **518400**    IN    A    212.18.248.112|
|ns3.samsung.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:112|ns3.samsung.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:112|
|ns4.samsung.centralnic-dns.com.    **172800**    IN    A    212.18.249.112|ns4.samsung.centralnic-dns.com.    **518400**    IN    A    212.18.249.112|
|ns4.samsung.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:112|ns4.samsung.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:112|
||**a.samsung.dyntld.net.    518400    IN    A    162.88.40.2**|
||**a.samsung.dyntld.net.    518400    IN    AAAA    2600:2000:3010:0:0:0:0:2**|
||**b.samsung.dyntld.net.    518400    IN    AAAA    2600:2000:3011:0:0:0:0:2**|
||**b.samsung.dyntld.net.    518400    IN    A    162.88.41.2**|
||**c.samsung.dyntld.net.    518400    IN    AAAA    2600:2000:3012:0:0:0:0:2**|
||**c.samsung.dyntld.net.    518400    IN    A    162.88.42.2**|
||**d.samsung.dyntld.net.    518400    IN    A    162.88.43.2**|
||**d.samsung.dyntld.net.    518400    IN    AAAA    2600:2000:3013:0:0:0:0:2**|
#
## maserati
|expected|actual|
|--------|---|
|maserati.        86400    IN    DS    **26605** **8** 2 **193BBCAAFE96B6E4C1FB29D6C85445ACEE4F86CA3197EA9922518D5241CC3A97**|maserati.        86400    IN    DS    **52146** **7** **1 901A94250210C575DD41938B4064DFFCE6B443DC**|
|a0.nic.maserati.    **172800**    IN    **A**    **65.22.124.33**|**maserati.        86400    IN    DS    52146 7 **2 **C798F7039F390F0851FF3C9AA3825ED0E971730AAA2143109185625DA8ADD7F1**|
|a0.nic.maserati.    **172800**    IN    **AAAA**    **2a01:8840:7a:0:0:0:0:33**|a0.nic.maserati.    **518400**    IN    **AAAA**    **2a01:8840:7a:0:0:0:0:33**|
|a2.nic.maserati.    **172800**    IN    A    65.22.127.33|a0.nic.maserati.    **518400**    IN    **A**    **65.22.124.33**|
|a2.nic.maserati.    **172800**    IN    AAAA    2a01:8840:7d:0:0:0:0:33|a2.nic.maserati.    **518400**    IN    A    65.22.127.33|
|b0.nic.maserati.    **172800**    IN    A    65.22.125.33|a2.nic.maserati.    **518400**    IN    AAAA    2a01:8840:7d:0:0:0:0:33|
|**b0**.nic.maserati.    **172800**    IN    AAAA    **2a01:8840:7b:0:0:0:0:33**|b0.nic.maserati.    **518400**    IN    **AAAA    2a01:8840:7b:0:0:0:0:33**|
|c0.nic.maserati.    **172800**    IN    A    65.22.126.33|**b0.nic.maserati.    518400    IN    **A    65.22.125.33|
|**c0.nic.maserati.    172800    IN    AAAA    2a01:8840:7c:0:0:0:0:33**|**c0**.nic.maserati.    **518400**    IN    AAAA    **2a01:8840:7c:0:0:0:0:33**|
||c0.nic.maserati.    **518400**    IN    A    65.22.126.33|
#
## lefrak
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## mobile
|expected|actual|
|--------|---|
|mobile.            86400    IN    DS    **85** **8** 2 **7E9719C718C3954D6F5D3C8967B1424F663AC3FF24D49BA6C26A52EBCD2C3B0F**|mobile.            86400    IN    DS    **57184** **7** **1 12A5CC9855C54529D7DEA1369928DFD9BBAF2ABE**|
|a0.nic.mobile.        **172800**    IN    **A**    **65.22.96.9**|**mobile.            86400    IN    DS    57184 7 **2 **15FF86AE7686124B5B00470D612746B2B4C100FE1C1963ACD6EA6326ED5FE8DE**|
|a0.nic.mobile.        **172800**    IN    **AAAA**    **2a01:8840:5e:0:0:0:0:9**|a0.nic.mobile.        **518400**    IN    **AAAA**    **2a01:8840:5e:0:0:0:0:9**|
|a2.nic.mobile.        **172800**    IN    A    65.22.99.9|a0.nic.mobile.        **518400**    IN    **A**    **65.22.96.9**|
|a2.nic.mobile.        **172800**    IN    AAAA    2a01:8840:61:0:0:0:0:9|a2.nic.mobile.        **518400**    IN    A    65.22.99.9|
|b0.nic.mobile.        **172800**    IN    A    65.22.97.9|a2.nic.mobile.        **518400**    IN    AAAA    2a01:8840:61:0:0:0:0:9|
|b0.nic.mobile.        **172800**    IN    AAAA    2a01:8840:5f:0:0:0:0:9|b0.nic.mobile.        **518400**    IN    A    65.22.97.9|
|c0.nic.mobile.        **172800**    IN    A    65.22.98.9|b0.nic.mobile.        **518400**    IN    AAAA    2a01:8840:5f:0:0:0:0:9|
|c0.nic.mobile.        **172800**    IN    AAAA    2a01:8840:60:0:0:0:0:9|c0.nic.mobile.        **518400**    IN    A    65.22.98.9|
||c0.nic.mobile.        **518400**    IN    AAAA    2a01:8840:60:0:0:0:0:9|
#
## rich
|expected|actual|
|--------|---|
|rich.            **86400**    IN    **DS**    **59100** **7 2 A80BED8F542403477B34A16DBE8795D05DAB2008ED9E9FE651ADA8D27215B66B**|**a0.nic.**rich.        **518400**    IN    **AAAA**    **2a01:8840:86:0:0:0:0:17**|
|a0.nic.rich.        **172800**    IN    A    65.22.136.17|a0.nic.rich.        **518400**    IN    A    65.22.136.17|
|**a0**.nic.rich.        **172800**    IN    AAAA    **2a01:8840:86:0:0:0:0:17**|**a2**.nic.rich.        **518400**    IN    AAAA    **2a01:8840:89:0:0:0:0:17**|
|a2.nic.rich.        **172800**    IN    A    65.22.139.17|a2.nic.rich.        **518400**    IN    A    65.22.139.17|
|**a2**.nic.rich.        **172800**    IN    AAAA    **2a01:8840:89:0:0:0:0:17**|**b0**.nic.rich.        **518400**    IN    AAAA    **2a01:8840:87:0:0:0:0:17**|
|b0.nic.rich.        **172800**    IN    A    65.22.137.17|b0.nic.rich.        **518400**    IN    A    65.22.137.17|
|**b0**.nic.rich.        **172800**    IN    AAAA    **2a01:8840:87:0:0:0:0:17**|**c0**.nic.rich.        **518400**    IN    AAAA    **2a01:8840:88:0:0:0:0:17**|
|c0.nic.rich.        **172800**    IN    A    65.22.138.17|c0.nic.rich.        **518400**    IN    A    65.22.138.17|
|**c0.nic.rich.        172800    IN    AAAA    2a01:8840:88:0:0:0:0:17**||
#
## linde
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## lundbeck
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## progressive
|expected|actual|
|--------|---|
|progressive.        86400    IN    DS    **17329** **8** 2 **F6623EFA3C197E122F7037A659F8E7FB2CEC4D91AF518653D04B44F15A72ABC9**|progressive.        86400    IN    DS    **17860** **7** **1 4A585DE14429F9B1E2CA4B0C451809FB215FF962**|
|a0.nic.progressive.    **172800**    IN    A    65.22.200.33|**progressive.        86400    IN    DS    17860 7 **2 **2919BDDDA258D0F505A33B1749945A7DF4689CD3639393401E28F8BFA16C18C0**|
|a0.nic.progressive.    **172800**    IN    AAAA    2a01:8840:c2:0:0:0:0:33|a0.nic.progressive.    **518400**    IN    A    65.22.200.33|
|a2.nic.progressive.    **172800**    IN    A    65.22.203.33|a0.nic.progressive.    **518400**    IN    AAAA    2a01:8840:c2:0:0:0:0:33|
|a2.nic.progressive.    **172800**    IN    AAAA    2a01:8840:c5:0:0:0:0:33|a2.nic.progressive.    **518400**    IN    A    65.22.203.33|
|b0.nic.progressive.    **172800**    IN    A    65.22.201.33|a2.nic.progressive.    **518400**    IN    AAAA    2a01:8840:c5:0:0:0:0:33|
|b0.nic.progressive.    **172800**    IN    AAAA    2a01:8840:c3:0:0:0:0:33|b0.nic.progressive.    **518400**    IN    A    65.22.201.33|
|c0.nic.progressive.    **172800**    IN    A    65.22.202.33|b0.nic.progressive.    **518400**    IN    AAAA    2a01:8840:c3:0:0:0:0:33|
|c0.nic.progressive.    **172800**    IN    AAAA    2a01:8840:c4:0:0:0:0:33|c0.nic.progressive.    **518400**    IN    A    65.22.202.33|
||c0.nic.progressive.    **518400**    IN    AAAA    2a01:8840:c4:0:0:0:0:33|
#
## genting
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## career
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xerox
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--otu796d
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## nab
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## airtel
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ril
|expected|actual|
|--------|---|
|ril.            86400    IN    DS    **19549** **8** **2** **AEBD50284035552652975D96493C1394E8C652C43AC366F019B0FED4CE3B5ABF**|ril.            86400    IN    DS    **62953** **7** **1** **0BE36F202719DBB172F1E771AD856928B3C7E2F1**|
|**a0.nic.**ril.        **172800**    IN    **A**    **65.22.180.17**|ril.            **86400**    IN    **DS**    **62953** **7 2 3295417336F81048BD61F840D192F33EA3164252B75856F95329CAE87A7BA5B1**|
|a0.nic.ril.        **172800**    IN    AAAA    2a01:8840:ae:0:0:0:0:17|a0.nic.ril.        **518400**    IN    AAAA    2a01:8840:ae:0:0:0:0:17|
|**a2**.nic.ril.        **172800**    IN    A    65.22.**183**.17|**a0**.nic.ril.        **518400**    IN    A    65.22.**180**.17|
|a2.nic.ril.        **172800**    IN    AAAA    2a01:8840:b1:0:0:0:0:17|a2.nic.ril.        **518400**    IN    AAAA    2a01:8840:b1:0:0:0:0:17|
|**b0**.nic.ril.        **172800**    IN    A    65.22.**181**.17|**a2**.nic.ril.        **518400**    IN    A    65.22.**183**.17|
|b0.nic.ril.        **172800**    IN    AAAA    2a01:8840:af:0:0:0:0:17|b0.nic.ril.        **518400**    IN    AAAA    2a01:8840:af:0:0:0:0:17|
|**c0**.nic.ril.        **172800**    IN    A    65.22.**182**.17|**b0**.nic.ril.        **518400**    IN    A    65.22.**181**.17|
|c0.nic.ril.        **172800**    IN    AAAA    2a01:8840:b0:0:0:0:0:17|c0.nic.ril.        **518400**    IN    AAAA    2a01:8840:b0:0:0:0:0:17|
||**c0.nic.ril.        518400    IN    A    65.22.182.17**|
#
## pet
|expected|actual|
|--------|---|
|pet.            86400    IN    DS    **42856** **8** 2 **EE6C6C84EFF7B00EB70D9BD8A29CEE8A04D29D4D006CC1F61A95FFF873FDE974**|pet.            86400    IN    DS    **55770** **7** **1 4DA7E881ABAE60550A8E530A9988B09CE90B48F8**|
|a0.nic.pet.        **172800**    IN    **A**    **65.22.16.17**|**pet.            86400    IN    DS    55770 7 **2 **2B9416B5422E475C1963E8374776A278814547AA49020DE2B2C79A186D0EA4D6**|
|a0.nic.pet.        **172800**    IN    **AAAA**    **2a01:8840:12:0:0:0:0:17**|a0.nic.pet.        **518400**    IN    **AAAA**    **2a01:8840:12:0:0:0:0:17**|
|a2.nic.pet.        **172800**    IN    A    65.22.19.17|a0.nic.pet.        **518400**    IN    **A**    **65.22.16.17**|
|a2.nic.pet.        **172800**    IN    AAAA    2a01:8840:15:0:0:0:0:17|a2.nic.pet.        **518400**    IN    A    65.22.19.17|
|b0.nic.pet.        **172800**    IN    **A**    **65.22.17.17**|a2.nic.pet.        **518400**    IN    AAAA    2a01:8840:15:0:0:0:0:17|
|b0.nic.pet.        **172800**    IN    **AAAA**    **2a01:8840:13:0:0:0:0:17**|b0.nic.pet.        **518400**    IN    **AAAA**    **2a01:8840:13:0:0:0:0:17**|
|c0.nic.pet.        **172800**    IN    A    65.22.18.17|b0.nic.pet.        **518400**    IN    **A**    **65.22.17.17**|
|c0.nic.pet.        **172800**    IN    AAAA    2a01:8840:14:0:0:0:0:17|c0.nic.pet.        **518400**    IN    A    65.22.18.17|
||c0.nic.pet.        **518400**    IN    AAAA    2a01:8840:14:0:0:0:0:17|
#
## xn--kput3i
|expected|actual|
|--------|---|
|xn--kput3i.        86400    IN    DS    **52711** **8** **2** **5F79E365D1534C004A0B4CA879766111ACCB9350241C0DE57CDFF36AB8CF87F1**|xn--kput3i.        86400    IN    DS    **63238** **7** **1** **914E46CEDD3D5584CF4A875DF104B16C6652C6FB**|
|**a0.nic.**xn--kput3i.    **172800**    IN    **A**    **65.22.216.1**|xn--kput3i.        **86400**    IN    **DS**    **63238** **7 2 733D6BE493CC3B34671CF4AEC50D7CCC5FA2685418AB52EE5F87F38DE98DA8CD**|
|a0.nic.xn--kput3i.    **172800**    IN    AAAA    2a01:8840:d2:0:0:0:0:1|a0.nic.xn--kput3i.    **518400**    IN    AAAA    2a01:8840:d2:0:0:0:0:1|
|**a2**.nic.xn--kput3i.    **172800**    IN    A    65.22.**219**.1|**a0**.nic.xn--kput3i.    **518400**    IN    A    65.22.**216**.1|
|a2.nic.xn--kput3i.    **172800**    IN    **AAAA**    **2a01:8840:d5:0:0:0:0:1**|a2.nic.xn--kput3i.    **518400**    IN    **A**    **65.22.219.1**|
|**b0**.nic.xn--kput3i.    **172800**    IN    **A**    **65.22.217.1**|**a2**.nic.xn--kput3i.    **518400**    IN    **AAAA**    **2a01:8840:d5:0:0:0:0:1**|
|b0.nic.xn--kput3i.    **172800**    IN    AAAA    2a01:8840:d3:0:0:0:0:1|b0.nic.xn--kput3i.    **518400**    IN    AAAA    2a01:8840:d3:0:0:0:0:1|
|**c0**.nic.xn--kput3i.    **172800**    IN    A    65.22.**218**.1|**b0**.nic.xn--kput3i.    **518400**    IN    A    65.22.**217**.1|
|c0.nic.xn--kput3i.    **172800**    IN    AAAA    2a01:8840:d4:0:0:0:0:1|c0.nic.xn--kput3i.    **518400**    IN    AAAA    2a01:8840:d4:0:0:0:0:1|
||**c0.nic.xn--kput3i.    518400    IN    A    65.22.218.1**|
#
## scjohnson
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--j6w193g
|expected|actual|
|--------|---|
|xn--j6w193g.        86400    IN    DS    **19067** 8 1 **50ED46D13E86C71AEC8F8E14C9BEF3E89BA9DE35**|xn--j6w193g.        86400    IN    DS    **26075** 8 1 **0133D22A9073FAA4A81DDAA0935CFC8BE26AC541**|
|xn--j6w193g.        86400    IN    DS    **19067** 8 2 **894C21F4F10720710D9D3B13643106918FD466F114DBA2F1F67A7BC0EBD237B3**|xn--j6w193g.        86400    IN    DS    **26075** 8 2 **D7D919FB2CD703F70081FDF3C8FA293809340280E1E07778C069AD59F2B33F4D**|
|c.hkirc.net.hk.        **172800**    IN    A    203.119.2.218|c.hkirc.net.hk.        **518400**    IN    **AAAA    2001:dca:4000:0:0:0:cb77:2da**|
|**c**.hkirc.net.hk.        **172800**    IN    AAAA    **2001:dca:4000:0:0:0:cb77:2da**|**c.hkirc.net.hk.        518400    IN    **A    203.119.2.218|
|d.hkirc.net.hk.        **172800**    IN    A    203.119.87.218|**d**.hkirc.net.hk.        **518400**    IN    AAAA    **2001:dca:2000:0:0:0:cb77:57da**|
|**d**.hkirc.net.hk.        **172800**    IN    AAAA    **2001:dca:2000:0:0:0:cb77:57da**|d.hkirc.net.hk.        **518400**    IN    A    203.119.87.218|
|t.hkirc.net.hk.        **172800**    IN    A    202.12.31.53|**t**.hkirc.net.hk.        **518400**    IN    AAAA    **2001:dd8:12:0:0:0:0:53**|
|**t**.hkirc.net.hk.        **172800**    IN    AAAA    **2001:dd8:12:0:0:0:0:53**|t.hkirc.net.hk.        **518400**    IN    A    202.12.31.53|
|u.hkirc.net.hk.        **172800**    IN    A    210.201.138.58|**u**.hkirc.net.hk.        **518400**    IN    AAAA    **2404:0:10a0:0:0:0:0:58**|
|**u**.hkirc.net.hk.        **172800**    IN    AAAA    **2404:0:10a0:0:0:0:0:58**|u.hkirc.net.hk.        **518400**    IN    A    210.201.138.58|
|v.hkirc.net.hk.        **172800**    IN    A    204.61.216.46|**v**.hkirc.net.hk.        **518400**    IN    AAAA    **2001:500:14:6046:ad:0:0:1**|
|**v.hkirc.net.hk.        172800    IN    AAAA    2001:500:14:6046:ad:0:0:1**|v.hkirc.net.hk.        **518400**    IN    A    204.61.216.46|
|x.hkirc.net.hk.        **172800**    IN    A    202.45.188.39|x.hkirc.net.hk.        **518400**    IN    A    202.45.188.39|
|x.hkirc.net.hk.        **172800**    IN    AAAA    2405:3001:1:3a:0:0:0:27|x.hkirc.net.hk.        **518400**    IN    AAAA    2405:3001:1:3a:0:0:0:27|
|y.hkirc.net.hk.        **172800**    IN    A    137.189.6.21|y.hkirc.net.hk.        **518400**    IN    A    137.189.6.21|
|y.hkirc.net.hk.        **172800**    IN    AAAA    2405:3000:3:6:0:0:0:15|y.hkirc.net.hk.        **518400**    IN    AAAA    2405:3000:3:6:0:0:0:15|
|z.hkirc.net.hk.        **172800**    IN    A    194.146.106.70|z.hkirc.net.hk.        **518400**    IN    A    194.146.106.70|
|z.hkirc.net.hk.        **172800**    IN    AAAA    2001:67c:1010:17:0:0:0:53|z.hkirc.net.hk.        **518400**    IN    AAAA    2001:67c:1010:17:0:0:0:53|
#
## xn--czru2d
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## pink
|expected|actual|
|--------|---|
|**pink.            172800    IN    NS    b2.nic.pink.**||
|pink.            86400    IN    DS    **53032** **8** 2 **54475C411977FB9C94C01453633EB43B8DC64B154462DE278A0644C6B83A79D1**|pink.            86400    IN    DS    **45756** **7** **1 D4496FF46E35CC9A206DA310B24C36AF205A2BD1**|
|a0.nic.pink.        **172800**    IN    A    65.22.28.17|**pink.            86400    IN    DS    45756 7 **2 **71CDA61FCA2B38FD3C93B8A69B2300CD7BC91FF32C306F1F3F831BBA7686A149**|
|a0.nic.pink.        **172800**    IN    AAAA    2a01:8840:1e:0:0:0:0:17|a0.nic.pink.        **518400**    IN    A    65.22.28.17|
|a2.nic.pink.        **172800**    IN    **A**    **65.22.31.17**|a0.nic.pink.        **518400**    IN    AAAA    2a01:8840:1e:0:0:0:0:17|
|a2.nic.pink.        **172800**    IN    **AAAA**    **2a01:8840:21:0:0:0:0:17**|a2.nic.pink.        **518400**    IN    **AAAA**    **2a01:8840:21:0:0:0:0:17**|
|b0.nic.pink.        **172800**    IN    A    65.22.29.17|a2.nic.pink.        **518400**    IN    **A**    **65.22.31.17**|
|b0.nic.pink.        **172800**    IN    AAAA    2a01:8840:1f:0:0:0:0:17|b0.nic.pink.        **518400**    IN    A    65.22.29.17|
|**b2**.nic.pink.        **172800**    IN    **A    65.22.31.21**|b0.nic.pink.        **518400**    IN    AAAA    2a01:8840:1f:0:0:0:0:17|
|**b2.nic.pink.        172800    IN    **AAAA    **2a01:8840:21:0:0:0:0:21**|**c0**.nic.pink.        **518400**    IN    AAAA    **2a01:8840:20:0:0:0:0:17**|
|c0.nic.pink.        **172800**    IN    A    65.22.30.17|c0.nic.pink.        **518400**    IN    A    65.22.30.17|
|**c0.nic.pink.        172800    IN    AAAA    2a01:8840:20:0:0:0:0:17**||
#
## protection
|expected|actual|
|--------|---|
|protection.        172800    IN    NS    **e**.nic.protection.|protection.        172800    IN    NS    **c**.nic.protection.|
|protection.        172800    IN    NS    **f**.nic.protection.|protection.        172800    IN    NS    **d**.nic.protection.|
|a.nic.protection.    **172800**    IN    **A**    **194.169.218.67**|a.nic.protection.    **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:67**|
|a.nic.protection.    **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:67**|a.nic.protection.    **518400**    IN    **A**    **194.169.218.67**|
|b.nic.protection.    **172800**    IN    A    185.24.64.67|b.nic.protection.    **518400**    IN    A    185.24.64.67|
|b.nic.protection.    **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:67|b.nic.protection.    **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:67|
|**e**.nic.protection.    **172800**    IN    A    **212**.**18**.**248**.**67**|**c**.nic.protection.    **518400**    IN    A    **185**.**38**.**99**.**10**|
|**e**.nic.protection.    **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:67**|**c**.nic.protection.    **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:10**|
|**f**.nic.protection.    **172800**    IN    A    **212**.**18**.**249**.**67**|**d**.nic.protection.    **518400**    IN    A    **108**.**59**.**161**.**10**|
|**f**.nic.protection.    **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:67**|**d**.nic.protection.    **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:10**|
#
## dabur
|expected|actual|
|--------|---|
|dabur.            86400    IN    DS    **12355** **8** 2 **BC18991E60B16ED8791D94EA935D83E9D40E2CBA9AC8B824A40191E5F5F50AE4**|dabur.            86400    IN    DS    **19761** **7** **1 07A2F4A7E8D08DE6E5E6447912E600B0DB1B6469**|
|a0.nic.dabur.        **172800**    IN    A    65.22.180.25|**dabur.            86400    IN    DS    19761 7 **2 **53A018FE3E95BFB559C780B1AD542730AD65F3D723D80749C2535CBE8DF83FC5**|
|a0.nic.dabur.        **172800**    IN    AAAA    2a01:8840:ae:0:0:0:0:25|a0.nic.dabur.        **518400**    IN    A    65.22.180.25|
|a2.nic.dabur.        **172800**    IN    A    65.22.183.25|a0.nic.dabur.        **518400**    IN    AAAA    2a01:8840:ae:0:0:0:0:25|
|a2.nic.dabur.        **172800**    IN    AAAA    2a01:8840:b1:0:0:0:0:25|a2.nic.dabur.        **518400**    IN    A    65.22.183.25|
|b0.nic.dabur.        **172800**    IN    A    65.22.181.25|a2.nic.dabur.        **518400**    IN    AAAA    2a01:8840:b1:0:0:0:0:25|
|b0.nic.dabur.        **172800**    IN    AAAA    2a01:8840:af:0:0:0:0:25|b0.nic.dabur.        **518400**    IN    A    65.22.181.25|
|c0.nic.dabur.        **172800**    IN    A    65.22.182.25|b0.nic.dabur.        **518400**    IN    AAAA    2a01:8840:af:0:0:0:0:25|
|c0.nic.dabur.        **172800**    IN    AAAA    2a01:8840:b0:0:0:0:0:25|c0.nic.dabur.        **518400**    IN    A    65.22.182.25|
||c0.nic.dabur.        **518400**    IN    AAAA    2a01:8840:b0:0:0:0:0:25|
#
## top
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## lancia
|expected|actual|
|--------|---|
|lancia.            86400    IN    DS    **29554** **8** **2** **BE7697AB47ACE6C5D414F7A2D14CE1A0C4E4E2AC392FB9A31A6BE506A3476A67**|lancia.            86400    IN    DS    **19923** **7** **1** **B5D8AD2D04FA910982AF961D28D7B967A8C6220F**|
|**a0.nic.**lancia.        **172800**    IN    **A**    **65.22.124.9**|lancia.            **86400**    IN    **DS**    **19923** **7 2 9BC26E45CDBF80BBE2119249681341FFF1F7B21FF6636DDF9C599ECB92369F94**|
|a0.nic.lancia.        **172800**    IN    AAAA    2a01:8840:7a:0:0:0:0:9|a0.nic.lancia.        **518400**    IN    AAAA    2a01:8840:7a:0:0:0:0:9|
|**a2**.nic.lancia.        **172800**    IN    A    65.22.**127**.9|**a0**.nic.lancia.        **518400**    IN    A    65.22.**124**.9|
|a2.nic.lancia.        **172800**    IN    AAAA    2a01:8840:7d:0:0:0:0:9|a2.nic.lancia.        **518400**    IN    AAAA    2a01:8840:7d:0:0:0:0:9|
|**b0**.nic.lancia.        **172800**    IN    A    65.22.**125**.9|**a2**.nic.lancia.        **518400**    IN    A    65.22.**127**.9|
|b0.nic.lancia.        **172800**    IN    AAAA    2a01:8840:7b:0:0:0:0:9|b0.nic.lancia.        **518400**    IN    AAAA    2a01:8840:7b:0:0:0:0:9|
|c0.nic.lancia.        **172800**    IN    A    65.22.126.9|**b0.nic.lancia.        518400    IN    A    65.22.125.9**|
|c0.nic.lancia.        **172800**    IN    AAAA    2a01:8840:7c:0:0:0:0:9|c0.nic.lancia.        **518400**    IN    A    65.22.126.9|
||c0.nic.lancia.        **518400**    IN    AAAA    2a01:8840:7c:0:0:0:0:9|
#
## mobi
|expected|actual|
|--------|---|
|mobi.            86400    IN    DS    **56191** **8** 2 **016C0D8022BEF2CABB827CE75DABD8FD24CD0160AC277A95ECD5E79B1A95592C**|mobi.            86400    IN    DS    **63018** **7** **1 CB9305B20DBC90CFD77685B61E805805A148A902**|
|a0.mobi.afilias-nst.info.    **172800**    IN    **A**    **199.254.55.1**|**mobi.            86400    IN    DS    63018 7 **2 **9E096946728A9B60D71957AE454A75F7AA03A62D44D26AA6BF702154A5307E2A**|
|a0.mobi.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:21:0:0:0:0:1**|a0.mobi.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:21:0:0:0:0:1**|
|a2.mobi.afilias-nst.info.    **172800**    IN    A    199.249.118.1|a0.mobi.afilias-nst.info.    **518400**    IN    **A**    **199.254.55.1**|
|a2.mobi.afilias-nst.info.    **172800**    IN    AAAA    2001:500:46:0:0:0:0:1|a2.mobi.afilias-nst.info.    **518400**    IN    A    199.249.118.1|
|c0.mobi.afilias-nst.info.    **172800**    IN    **A**    **199.254.57.1**|a2.mobi.afilias-nst.info.    **518400**    IN    AAAA    2001:500:46:0:0:0:0:1|
|c0.mobi.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:23:0:0:0:0:1**|c0.mobi.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:23:0:0:0:0:1**|
|b0.mobi.afilias-nst.org.    **172800**    IN    **A**    **199.254.56.1**|c0.mobi.afilias-nst.info.    **518400**    IN    **A**    **199.254.57.1**|
|b0.mobi.afilias-nst.org.    **172800**    IN    **AAAA**    **2001:500:22:0:0:0:0:1**|b0.mobi.afilias-nst.org.    **518400**    IN    **AAAA**    **2001:500:22:0:0:0:0:1**|
|b2.mobi.afilias-nst.org.    **172800**    IN    A    199.249.126.1|b0.mobi.afilias-nst.org.    **518400**    IN    **A**    **199.254.56.1**|
|b2.mobi.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4e:0:0:0:0:1|b2.mobi.afilias-nst.org.    **518400**    IN    A    199.249.126.1|
|d0.mobi.afilias-nst.org.    **172800**    IN    A    199.254.58.1|b2.mobi.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4e:0:0:0:0:1|
|d0.mobi.afilias-nst.org.    **172800**    IN    AAAA    2001:500:24:0:0:0:0:1|d0.mobi.afilias-nst.org.    **518400**    IN    A    199.254.58.1|
||d0.mobi.afilias-nst.org.    **518400**    IN    AAAA    2001:500:24:0:0:0:0:1|
#
## tiaa
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## dunlop
|expected|actual|
|--------|---|
|dunlop.            86400    IN    DS    **22897** **8** 2 **03CD996F132FFD32BC1BB4F08122D4A4F6570BB9C2AB647BE9B1AF174E79AFAA**|dunlop.            86400    IN    DS    **47101** **7** **1 FB296A6C4E674B9359746AD3A43F18059A831455**|
|a0.nic.dunlop.        **172800**    IN    A    65.22.120.33|**dunlop.            86400    IN    DS    47101 7 **2 **E93007312AB67EE11773A50AA33357011D6DBA8E9445E418B445735CC4FBD47D**|
|a0.nic.dunlop.        **172800**    IN    AAAA    2a01:8840:76:0:0:0:0:33|a0.nic.dunlop.        **518400**    IN    A    65.22.120.33|
|a2.nic.dunlop.        **172800**    IN    A    65.22.123.33|a0.nic.dunlop.        **518400**    IN    AAAA    2a01:8840:76:0:0:0:0:33|
|a2.nic.dunlop.        **172800**    IN    AAAA    2a01:8840:79:0:0:0:0:33|a2.nic.dunlop.        **518400**    IN    A    65.22.123.33|
|b0.nic.dunlop.        **172800**    IN    **A**    **65.22.121.33**|a2.nic.dunlop.        **518400**    IN    AAAA    2a01:8840:79:0:0:0:0:33|
|b0.nic.dunlop.        **172800**    IN    **AAAA**    **2a01:8840:77:0:0:0:0:33**|b0.nic.dunlop.        **518400**    IN    **AAAA**    **2a01:8840:77:0:0:0:0:33**|
|c0.nic.dunlop.        **172800**    IN    A    65.22.122.33|b0.nic.dunlop.        **518400**    IN    **A**    **65.22.121.33**|
|c0.nic.dunlop.        **172800**    IN    AAAA    2a01:8840:78:0:0:0:0:33|c0.nic.dunlop.        **518400**    IN    A    65.22.122.33|
||c0.nic.dunlop.        **518400**    IN    AAAA    2a01:8840:78:0:0:0:0:33|
#
## shaw
|expected|actual|
|--------|---|
|shaw.            **86400**    IN    **DS**    **58053** **7 2 2042FE94BF6560EDB3A4579015981590594F887AF440674C35EF26166FECC116**|**a0.nic.**shaw.        **518400**    IN    **AAAA**    **2a01:8840:56:0:0:0:0:17**|
|a0.nic.shaw.        **172800**    IN    A    65.22.88.17|a0.nic.shaw.        **518400**    IN    A    65.22.88.17|
|**a0.nic.shaw.        172800    IN    AAAA    2a01:8840:56:0:0:0:0:17**|a2.nic.shaw.        **518400**    IN    A    65.22.91.17|
|a2.nic.shaw.        **172800**    IN    A    65.22.91.17|a2.nic.shaw.        **518400**    IN    AAAA    2a01:8840:59:0:0:0:0:17|
|a2.nic.shaw.        **172800**    IN    AAAA    2a01:8840:59:0:0:0:0:17|b0.nic.shaw.        **518400**    IN    **AAAA**    **2a01:8840:57:0:0:0:0:17**|
|b0.nic.shaw.        **172800**    IN    **A**    **65.22.89.17**|b0.nic.shaw.        **518400**    IN    **A**    **65.22.89.17**|
|b0.nic.shaw.        **172800**    IN    **AAAA**    **2a01:8840:57:0:0:0:0:17**|c0.nic.shaw.        **518400**    IN    A    65.22.90.17|
|c0.nic.shaw.        **172800**    IN    A    65.22.90.17|c0.nic.shaw.        **518400**    IN    AAAA    2a01:8840:58:0:0:0:0:17|
|c0.nic.shaw.        **172800**    IN    AAAA    2a01:8840:58:0:0:0:0:17||
#
## com
|expected|actual|
|--------|---|
|**com.            86400    IN    DS    30909 8 2 E2D3C916F6DEEAC73294E8268FB5885044A833FC5459588F4A9184CFC41A5766**||
|a.gtld-servers.net.    **172800**    IN    A    192.5.6.30|**com.            86400    IN    DS    30909 8 2 E2D3C916F6DEEAC73294E8268FB5885044A833FC5459588F4A9184CFC41A5766**|
|**a**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:a83e:0:0:0:2:30**|a.gtld-servers.net.    **518400**    IN    **AAAA    2001:503:a83e:0:0:0:2:30**|
|b.gtld-servers.net.    **172800**    IN    A    192.33.14.30|**a.gtld-servers.net.    518400    IN    **A    192.5.6.30|
|**b**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:231d:0:0:0:2:30**|**b**.gtld-servers.net.    **518400**    IN    AAAA    **2001:503:231d:0:0:0:2:30**|
|c.gtld-servers.net.    **172800**    IN    A    192.26.92.30|b.gtld-servers.net.    **518400**    IN    A    192.33.14.30|
|**c**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:83eb:0:0:0:0:30**|**c**.gtld-servers.net.    **518400**    IN    AAAA    **2001:503:83eb:0:0:0:0:30**|
|d.gtld-servers.net.    **172800**    IN    A    192.31.80.30|c.gtld-servers.net.    **518400**    IN    A    192.26.92.30|
|**d**.gtld-servers.net.    **172800**    IN    AAAA    **2001:500:856e:0:0:0:0:30**|**d**.gtld-servers.net.    **518400**    IN    AAAA    **2001:500:856e:0:0:0:0:30**|
|e.gtld-servers.net.    **172800**    IN    A    192.12.94.30|d.gtld-servers.net.    **518400**    IN    A    192.31.80.30|
|**e**.gtld-servers.net.    **172800**    IN    **AAAA**    **2001:502:1ca1:0:0:0:0:30**|**e**.gtld-servers.net.    **518400**    IN    AAAA    **2001:502:1ca1:0:0:0:0:30**|
|f.gtld-servers.net.    **172800**    IN    **A**    **192.35.51.30**|e.gtld-servers.net.    **518400**    IN    A    192.12.94.30|
|**f**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:d414:0:0:0:0:30**|**f**.gtld-servers.net.    **518400**    IN    **A**    **192.35.51.30**|
|g.gtld-servers.net.    **172800**    IN    A    192.42.93.30|f.gtld-servers.net.    **518400**    IN    **AAAA**    **2001:503:d414:0:0:0:0:30**|
|**g**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:eea3:0:0:0:0:30**|**g**.gtld-servers.net.    **518400**    IN    AAAA    **2001:503:eea3:0:0:0:0:30**|
|h.gtld-servers.net.    **172800**    IN    A    192.54.112.30|g.gtld-servers.net.    **518400**    IN    A    192.42.93.30|
|**h.gtld-servers.net.    172800    IN    AAAA    2001:502:8cc:0:0:0:0:30**|**h**.gtld-servers.net.    **518400**    IN    AAAA    **2001:502:8cc:0:0:0:0:30**|
|i.gtld-servers.net.    **172800**    IN    A    192.43.172.30|h.gtld-servers.net.    **518400**    IN    A    192.54.112.30|
|i.gtld-servers.net.    **172800**    IN    AAAA    2001:503:39c1:0:0:0:0:30|i.gtld-servers.net.    **518400**    IN    A    192.43.172.30|
|j.gtld-servers.net.    **172800**    IN    **A**    **192.48.79.30**|i.gtld-servers.net.    **518400**    IN    AAAA    2001:503:39c1:0:0:0:0:30|
|j.gtld-servers.net.    **172800**    IN    **AAAA**    **2001:502:7094:0:0:0:0:30**|j.gtld-servers.net.    **518400**    IN    **AAAA**    **2001:502:7094:0:0:0:0:30**|
|k.gtld-servers.net.    **172800**    IN    A    192.52.178.30|j.gtld-servers.net.    **518400**    IN    **A**    **192.48.79.30**|
|k.gtld-servers.net.    **172800**    IN    AAAA    2001:503:d2d:0:0:0:0:30|k.gtld-servers.net.    **518400**    IN    A    192.52.178.30|
|l.gtld-servers.net.    **172800**    IN    A    192.41.162.30|k.gtld-servers.net.    **518400**    IN    AAAA    2001:503:d2d:0:0:0:0:30|
|l.gtld-servers.net.    **172800**    IN    AAAA    2001:500:d937:0:0:0:0:30|l.gtld-servers.net.    **518400**    IN    A    192.41.162.30|
|m.gtld-servers.net.    **172800**    IN    A    192.55.83.30|l.gtld-servers.net.    **518400**    IN    AAAA    2001:500:d937:0:0:0:0:30|
|m.gtld-servers.net.    **172800**    IN    AAAA    **2001:501:b1f9:0:0:0:0:30**|m.gtld-servers.net.    **518400**    IN    A    192.55.83.30|
||m.gtld-servers.net.    **518400**    IN    AAAA    **2001:501:b1f9:0:0:0:0:31**|
#
## pccw
|expected|actual|
|--------|---|
|pccw.            86400    IN    DS    **43702** **8** 2 **59E6008039A16F566F18227380A702F8168707059629DA13CBFB9D1203E5EF93**|pccw.            86400    IN    DS    **29298** **7** **1 998AE96427D35E96D90B99BAF3A79BDEC3C34BFC**|
|a0.nic.pccw.        **172800**    IN    A    65.22.116.41|**pccw.            86400    IN    DS    29298 7 **2 **78DAB43D4C64A9408DB1AE27F1AF13B10ED452CFF04F5D91057CA8FA089A7553**|
|a0.nic.pccw.        **172800**    IN    AAAA    2a01:8840:72:0:0:0:0:41|a0.nic.pccw.        **518400**    IN    A    65.22.116.41|
|a2.nic.pccw.        **172800**    IN    A    65.22.119.41|a0.nic.pccw.        **518400**    IN    AAAA    2a01:8840:72:0:0:0:0:41|
|a2.nic.pccw.        **172800**    IN    AAAA    2a01:8840:75:0:0:0:0:41|a2.nic.pccw.        **518400**    IN    A    65.22.119.41|
|b0.nic.pccw.        **172800**    IN    A    65.22.117.41|a2.nic.pccw.        **518400**    IN    AAAA    2a01:8840:75:0:0:0:0:41|
|**b0**.nic.pccw.        **172800**    IN    AAAA    **2a01:8840:73:0:0:0:0:41**|b0.nic.pccw.        **518400**    IN    **AAAA    2a01:8840:73:0:0:0:0:41**|
|c0.nic.pccw.        **172800**    IN    A    65.22.118.41|**b0.nic.pccw.        518400    IN    **A    65.22.117.41|
|**c0.nic.pccw.        172800    IN    AAAA    2a01:8840:74:0:0:0:0:41**|**c0**.nic.pccw.        **518400**    IN    AAAA    **2a01:8840:74:0:0:0:0:41**|
||c0.nic.pccw.        **518400**    IN    A    65.22.118.41|
#
## hermes
|expected|actual|
|--------|---|
|**hermes.            86400    IN    DS    20683 7 2 DF1B7E3B0F481E723980733F1F23ECE440FF02C7F4A27649BFEDED4F17D9C62B**||
|a0.nic.hermes.        **172800**    IN    A    65.22.232.25|a0.nic.hermes.        **518400**    IN    **AAAA    2a01:8840:e2:0:0:0:0:25**|
|**a0**.nic.hermes.        **172800**    IN    AAAA    **2a01:8840:e2:0:0:0:0:25**|**a0.nic.hermes.        518400    IN    **A    65.22.232.25|
|a2.nic.hermes.        **172800**    IN    A    65.22.235.25|**a2**.nic.hermes.        **518400**    IN    AAAA    **2a01:8840:e5:0:0:0:0:25**|
|**a2**.nic.hermes.        **172800**    IN    AAAA    **2a01:8840:e5:0:0:0:0:25**|a2.nic.hermes.        **518400**    IN    A    65.22.235.25|
|b0.nic.hermes.        **172800**    IN    A    65.22.233.25|**b0**.nic.hermes.        **518400**    IN    AAAA    **2a01:8840:e3:0:0:0:0:25**|
|**b0**.nic.hermes.        **172800**    IN    AAAA    **2a01:8840:e3:0:0:0:0:25**|b0.nic.hermes.        **518400**    IN    A    65.22.233.25|
|c0.nic.hermes.        **172800**    IN    A    65.22.234.25|**c0**.nic.hermes.        **518400**    IN    AAAA    **2a01:8840:e4:0:0:0:0:25**|
|**c0.nic.hermes.        172800    IN    AAAA    2a01:8840:e4:0:0:0:0:25**|c0.nic.hermes.        **518400**    IN    A    65.22.234.25|
#
## net
|expected|actual|
|--------|---|
|a.gtld-servers.net.    **172800**    IN    A    192.5.6.30|a.gtld-servers.net.    **518400**    IN    **AAAA    2001:503:a83e:0:0:0:2:30**|
|**a**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:a83e:0:0:0:2:30**|**a.gtld-servers.net.    518400    IN    **A    192.5.6.30|
|b.gtld-servers.net.    **172800**    IN    A    192.33.14.30|**b**.gtld-servers.net.    **518400**    IN    AAAA    **2001:503:231d:0:0:0:2:30**|
|**b**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:231d:0:0:0:2:30**|b.gtld-servers.net.    **518400**    IN    A    192.33.14.30|
|c.gtld-servers.net.    **172800**    IN    A    192.26.92.30|**c**.gtld-servers.net.    **518400**    IN    AAAA    **2001:503:83eb:0:0:0:0:30**|
|**c**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:83eb:0:0:0:0:30**|c.gtld-servers.net.    **518400**    IN    A    192.26.92.30|
|d.gtld-servers.net.    **172800**    IN    A    192.31.80.30|**d**.gtld-servers.net.    **518400**    IN    AAAA    **2001:500:856e:0:0:0:0:30**|
|**d**.gtld-servers.net.    **172800**    IN    AAAA    **2001:500:856e:0:0:0:0:30**|d.gtld-servers.net.    **518400**    IN    A    192.31.80.30|
|e.gtld-servers.net.    **172800**    IN    A    192.12.94.30|**e**.gtld-servers.net.    **518400**    IN    AAAA    **2001:502:1ca1:0:0:0:0:30**|
|**e**.gtld-servers.net.    **172800**    IN    **AAAA**    **2001:502:1ca1:0:0:0:0:30**|e.gtld-servers.net.    **518400**    IN    A    192.12.94.30|
|f.gtld-servers.net.    **172800**    IN    **A**    **192.35.51.30**|**f**.gtld-servers.net.    **518400**    IN    **A**    **192.35.51.30**|
|**f**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:d414:0:0:0:0:30**|f.gtld-servers.net.    **518400**    IN    **AAAA**    **2001:503:d414:0:0:0:0:30**|
|g.gtld-servers.net.    **172800**    IN    A    192.42.93.30|**g**.gtld-servers.net.    **518400**    IN    AAAA    **2001:503:eea3:0:0:0:0:30**|
|**g**.gtld-servers.net.    **172800**    IN    AAAA    **2001:503:eea3:0:0:0:0:30**|g.gtld-servers.net.    **518400**    IN    A    192.42.93.30|
|h.gtld-servers.net.    **172800**    IN    A    192.54.112.30|**h**.gtld-servers.net.    **518400**    IN    AAAA    **2001:502:8cc:0:0:0:0:30**|
|**h.gtld-servers.net.    172800    IN    AAAA    2001:502:8cc:0:0:0:0:30**|h.gtld-servers.net.    **518400**    IN    A    192.54.112.30|
|i.gtld-servers.net.    **172800**    IN    A    192.43.172.30|i.gtld-servers.net.    **518400**    IN    A    192.43.172.30|
|i.gtld-servers.net.    **172800**    IN    AAAA    2001:503:39c1:0:0:0:0:30|i.gtld-servers.net.    **518400**    IN    AAAA    2001:503:39c1:0:0:0:0:30|
|j.gtld-servers.net.    **172800**    IN    **A**    **192.48.79.30**|j.gtld-servers.net.    **518400**    IN    **AAAA**    **2001:502:7094:0:0:0:0:30**|
|j.gtld-servers.net.    **172800**    IN    **AAAA**    **2001:502:7094:0:0:0:0:30**|j.gtld-servers.net.    **518400**    IN    **A**    **192.48.79.30**|
|k.gtld-servers.net.    **172800**    IN    A    192.52.178.30|k.gtld-servers.net.    **518400**    IN    A    192.52.178.30|
|k.gtld-servers.net.    **172800**    IN    AAAA    2001:503:d2d:0:0:0:0:30|k.gtld-servers.net.    **518400**    IN    AAAA    2001:503:d2d:0:0:0:0:30|
|l.gtld-servers.net.    **172800**    IN    A    192.41.162.30|l.gtld-servers.net.    **518400**    IN    A    192.41.162.30|
|l.gtld-servers.net.    **172800**    IN    AAAA    2001:500:d937:0:0:0:0:30|l.gtld-servers.net.    **518400**    IN    AAAA    2001:500:d937:0:0:0:0:30|
|m.gtld-servers.net.    **172800**    IN    A    192.55.83.30|m.gtld-servers.net.    **518400**    IN    A    192.55.83.30|
|m.gtld-servers.net.    **172800**    IN    AAAA    **2001:501:b1f9:0:0:0:0:30**|m.gtld-servers.net.    **518400**    IN    AAAA    **2001:501:b1f9:0:0:0:0:31**|
#
## xn--mk1bu44c
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## lat
|expected|actual|
|--------|---|
|lat.            86400    IN    DS    **58444** 8 2 **F14F358BE16FFABADAFC9E8BAD037978F2B04B3B180BAA82141BFD85F3B42726**|lat.            86400    IN    DS    **51802** 8 2 **3A561EC32168F35264981F2952AEF94E97654919AA5904CE1058C1D000F07492**|
|c.mx-ns.mx.        **172800**    IN    A    192.100.224.1|c.mx-ns.mx.        **518400**    IN    A    192.100.224.1|
|c.mx-ns.mx.        **172800**    IN    AAAA    2001:1258:0:0:0:0:0:1|c.mx-ns.mx.        **518400**    IN    AAAA    2001:1258:0:0:0:0:0:1|
|e.mx-ns.mx.        **172800**    IN    A    189.201.244.1|e.mx-ns.mx.        **518400**    IN    A    189.201.244.1|
|i.mx-ns.mx.        **172800**    IN    A    207.248.68.1|i.mx-ns.mx.        **518400**    IN    A    207.248.68.1|
|m.mx-ns.mx.        **172800**    IN    **A**    **200.94.176.1**|m.mx-ns.mx.        **518400**    IN    **AAAA**    **2001:13c7:7000:0:0:0:0:1**|
|m.mx-ns.mx.        **172800**    IN    **AAAA**    **2001:13c7:7000:0:0:0:0:1**|m.mx-ns.mx.        **518400**    IN    **A**    **200.94.176.1**|
|o.mx-ns.mx.        **172800**    IN    A    200.23.1.1|o.mx-ns.mx.        **518400**    IN    A    200.23.1.1|
|x.mx-ns.mx.        **172800**    IN    A    201.131.252.1|x.mx-ns.mx.        **518400**    IN    A    201.131.252.1|
#
## markets
|expected|actual|
|--------|---|
|markets.        **86400**    IN    **DS**    **9644** **8** **2** **82BE670A03A9B3B10697FEF833108CC0360C9EC729378C64E5DBEB6F3CB3FF0F**|markets.        **172800**    IN    **NS**    **ac1.nstld.com.**|
||**markets.**        **172800**    **IN    NS    ac2.nstld.com.**|
||**markets.        172800    IN    NS    ac3.nstld.com.**|
||**markets.        172800    IN    NS    ac4.nstld.com.**|
|**markets**.**        172800    IN    NS    a**.**nic**.**markets.**|**ac1**.**nstld**.**com**.        **518400**    IN    **A**    **192**.**42**.**176**.**30**|
|**markets.**        **172800    **IN    **NS**    **b**.**nic**.**markets**.|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**markets**.**        172800    IN    NS    c**.**nic**.**markets.**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**markets.**        **172800    **IN    **NS    d.nic.markets.**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**a.nic.markets.        172800    IN    **A    **194**.**169**.**218**.**123**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**a**.**nic**.**markets**.        **172800**    IN    AAAA    **2001:67c:13cc:0:0:0:1:123**|**ac4**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:123:0:0:0:0:30**|
|**b**.**nic**.**markets**.        **172800**    IN    A    **185**.**24**.**64**.**123**|**ac4**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**b**.**nic**.**markets**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:123**||
|**c**.**nic**.**markets**.        **172800**    IN    **A    212.18.248.123**||
|**c.nic.markets.        172800    IN    **AAAA    **2a04:2b00:13ee:0:0:0:0:123**||
|**d**.**nic**.**markets**.        **172800**    IN    A    **212**.**18**.**249**.**123**||
|**d.nic.markets.        172800    IN    AAAA    2a04:2b00:13ff:0:0:0:0:123**||
#
## versicherung
|expected|actual|
|--------|---|
|**versicherung.        86400    IN    DS    20576 8 2 EFD54D9277685E2B353D54E7ABADFFC424DEBD8028D7F444119E8B36C0117466**||
|a.dns.nic.versicherung.    **172800**    IN    **A**    **194.0.25.13**|**versicherung.        86400    IN    DS    50227 8 2 5D0D0DA59BE4750137E7B2B9E44C5A5CC19D5C7CDF5BB542ADB7630FF3D1FB90**|
|a.dns.nic.versicherung.    **172800**    IN    **AAAA**    **2001:678:20:0:0:0:0:13**|a.dns.nic.versicherung.    **518400**    IN    **AAAA**    **2001:678:20:0:0:0:0:13**|
|m.dns.nic.versicherung.    **172800**    IN    A    194.0.26.2|a.dns.nic.versicherung.    **518400**    IN    **A**    **194.0.25.13**|
|m.dns.nic.versicherung.    **172800**    IN    AAAA    2001:67c:10e0:0:0:0:0:2|m.dns.nic.versicherung.    **518400**    IN    A    194.0.26.2|
|n.dns.nic.versicherung.    **172800**    IN    **A**    **194.0.24.2**|m.dns.nic.versicherung.    **518400**    IN    AAAA    2001:67c:10e0:0:0:0:0:2|
|n.dns.nic.versicherung.    **172800**    IN    **AAAA**    **2001:678:24:0:0:0:0:2**|n.dns.nic.versicherung.    **518400**    IN    **AAAA**    **2001:678:24:0:0:0:0:2**|
||n.dns.nic.versicherung.    **518400**    IN    **A**    **194.0.24.2**|
#
## trv
|expected|actual|
|--------|---|
|trv.            86400    IN    DS    **48547** **8** 2 **F525871EE63FFED32856BA0C67F5115D5B011A437B67250E357DF2BDCF1EA31C**|trv.            86400    IN    DS    **53416** **7** **1 00A50A406DEE0482435EDB37C750A86FBEE0EB6A**|
|a0.nic.trv.        **172800**    IN    A    65.22.200.25|**trv.            86400    IN    DS    53416 7 **2 **4D298B83528835C23D343234F338E2F1A8857740D68D2BFA737159CF0B33B926**|
|a0.nic.trv.        **172800**    IN    AAAA    2a01:8840:c2:0:0:0:0:25|a0.nic.trv.        **518400**    IN    A    65.22.200.25|
|a2.nic.trv.        **172800**    IN    A    65.22.203.25|a0.nic.trv.        **518400**    IN    AAAA    2a01:8840:c2:0:0:0:0:25|
|a2.nic.trv.        **172800**    IN    AAAA    2a01:8840:c5:0:0:0:0:25|a2.nic.trv.        **518400**    IN    A    65.22.203.25|
|b0.nic.trv.        **172800**    IN    A    65.22.201.25|a2.nic.trv.        **518400**    IN    AAAA    2a01:8840:c5:0:0:0:0:25|
|b0.nic.trv.        **172800**    IN    AAAA    2a01:8840:c3:0:0:0:0:25|b0.nic.trv.        **518400**    IN    A    65.22.201.25|
|c0.nic.trv.        **172800**    IN    A    65.22.202.25|b0.nic.trv.        **518400**    IN    AAAA    2a01:8840:c3:0:0:0:0:25|
|c0.nic.trv.        **172800**    IN    AAAA    2a01:8840:c4:0:0:0:0:25|c0.nic.trv.        **518400**    IN    A    65.22.202.25|
||c0.nic.trv.        **518400**    IN    AAAA    2a01:8840:c4:0:0:0:0:25|
#
## shiksha
|expected|actual|
|--------|---|
|shiksha.        86400    IN    DS    **54049** **8** 2 **B4DD9094C19C5A3BE8D6921D695F16CD6412258FA8302E5D7879405E2C0EF7DC**|shiksha.        86400    IN    DS    **19339** **7** **1 A8F93C5CA81D7F38880F12CAD5D43F8BC522747C**|
|a0.nic.shiksha.        **172800**    IN    A    65.22.32.33|**shiksha.        86400    IN    DS    19339 7 **2 **CCDBBE400E7FCE7C2CAF32B1315D1CDF09289E69988ABD89A9E0A4280D0752AD**|
|a0.nic.shiksha.        **172800**    IN    AAAA    2a01:8840:22:0:0:0:0:33|a0.nic.shiksha.        **518400**    IN    A    65.22.32.33|
|a2.nic.shiksha.        **172800**    IN    A    65.22.35.33|a0.nic.shiksha.        **518400**    IN    AAAA    2a01:8840:22:0:0:0:0:33|
|**a2**.nic.shiksha.        **172800**    IN    AAAA    **2a01:8840:25:0:0:0:0:33**|a2.nic.shiksha.        **518400**    IN    **AAAA    2a01:8840:25:0:0:0:0:33**|
|b0.nic.shiksha.        **172800**    IN    A    65.22.33.33|**a2.nic.shiksha.        518400    IN    **A    65.22.35.33|
|**b0.nic.shiksha.        172800    IN    AAAA    2a01:8840:23:0:0:0:0:33**|**b0**.nic.shiksha.        **518400**    IN    AAAA    **2a01:8840:23:0:0:0:0:33**|
|c0.nic.shiksha.        **172800**    IN    AAAA    2a01:8840:24:0:0:0:0:33|b0.nic.shiksha.        **518400**    IN    A    65.22.33.33|
|c0.nic.shiksha.        **172800**    IN    A    65.22.34.33|c0.nic.shiksha.        **518400**    IN    AAAA    2a01:8840:24:0:0:0:0:33|
||c0.nic.shiksha.        **518400**    IN    A    65.22.34.33|
#
## kosher
|expected|actual|
|--------|---|
|**kosher.            86400    IN    DS    13510 7 2 AFA97E1C73ADDDF30D2E3A8F221E7F4CB3CAC134E54D74F157DC0BE1D7C2B9B0**||
|a0.nic.kosher.        **172800**    IN    A    65.22.220.1|a0.nic.kosher.        **518400**    IN    A    65.22.220.1|
|a0.nic.kosher.        **172800**    IN    AAAA    2a01:8840:d6:0:0:0:0:1|a0.nic.kosher.        **518400**    IN    AAAA    2a01:8840:d6:0:0:0:0:1|
|a2.nic.kosher.        **172800**    IN    A    65.22.223.1|a2.nic.kosher.        **518400**    IN    A    65.22.223.1|
|a2.nic.kosher.        **172800**    IN    AAAA    2a01:8840:d9:0:0:0:0:1|a2.nic.kosher.        **518400**    IN    AAAA    2a01:8840:d9:0:0:0:0:1|
|b0.nic.kosher.        **172800**    IN    **A**    **65.22.221.1**|b0.nic.kosher.        **518400**    IN    **AAAA**    **2a01:8840:d7:0:0:0:0:1**|
|b0.nic.kosher.        **172800**    IN    **AAAA**    **2a01:8840:d7:0:0:0:0:1**|b0.nic.kosher.        **518400**    IN    **A**    **65.22.221.1**|
|c0.nic.kosher.        **172800**    IN    A    65.22.222.1|c0.nic.kosher.        **518400**    IN    A    65.22.222.1|
|c0.nic.kosher.        **172800**    IN    AAAA    2a01:8840:d8:0:0:0:0:1|c0.nic.kosher.        **518400**    IN    AAAA    2a01:8840:d8:0:0:0:0:1|
#
## arpa
|expected|actual|
|--------|---|
|**a.root-servers.net.    518400    IN    A    198.41.0.4**||
|**b**.root-servers.net.    518400    IN    A    199.9.14.**201**|**a**.root-servers.net.    518400    IN    A    **198.41.0.4**|
||**a.root-servers.net.    518400    IN    A    **199.9.14.**207**|
|**c**.root-servers.net.    518400    IN    A    **192**.**33**.**4**.**12**|**b**.root-servers.net.    518400    IN    A    **199**.**9**.**14**.**201**|
|**d**.root-servers.net.    518400    IN    A    **199**.**7**.**91**.**13**|**c**.root-servers.net.    518400    IN    A    **192**.**33**.**4**.**12**|
||**d.root-servers.net.    518400    IN    A    199.7.91.13**|
|**h.root-servers.net.    518400    IN    A    198.97.190.53**||
|**i**.root-servers.net.    518400    IN    A    **192**.**36**.**148**.**17**|**h**.root-servers.net.    518400    IN    A    **198**.**97**.**190**.**53**|
|**k**.root-servers.net.    518400    IN    A    **193**.**0**.**14**.**129**|**i**.root-servers.net.    518400    IN    A    **192**.**36**.**148**.**17**|
|**l**.root-servers.net.    518400    IN    A    **199**.**7**.**83**.**42**|**k**.root-servers.net.    518400    IN    A    **193**.**0**.**14**.**129**|
||**l.root-servers.net.    518400    IN    A    199.7.83.42**|
#
## ngo
|expected|actual|
|--------|---|
|ngo.            86400    IN    DS    **23944** **8** 2 **DFEC23291372BA32BC2BDE96F88A383373BE1C4BA7BCDB65D5E34F1607400F63**|ngo.            86400    IN    DS    **61593** **7** **1 668811DA52ABBD23D8CE739514F28CFCE6E4BBE7**|
|a0.nic.ngo.        **172800**    IN    **A**    **199.19.56.1**|**ngo.            86400    IN    DS    61593 7 **2 **31FFE6B3994B6317DAC14D3AA82FBAB2FF9039706F678E95AA914889B5A7D3D8**|
|a0.nic.ngo.        **172800**    IN    **AAAA**    **2001:500:e:0:0:0:0:1**|a0.nic.ngo.        **518400**    IN    **AAAA**    **2001:500:e:0:0:0:0:1**|
|a2.nic.ngo.        **172800**    IN    A    199.249.112.1|a0.nic.ngo.        **518400**    IN    **A**    **199.19.56.1**|
|a2.nic.ngo.        **172800**    IN    AAAA    2001:500:40:0:0:0:0:1|a2.nic.ngo.        **518400**    IN    A    199.249.112.1|
|b0.nic.ngo.        **172800**    IN    A    199.19.54.1|a2.nic.ngo.        **518400**    IN    AAAA    2001:500:40:0:0:0:0:1|
|b0.nic.ngo.        **172800**    IN    AAAA    2001:500:c:0:0:0:0:1|b0.nic.ngo.        **518400**    IN    A    199.19.54.1|
|b2.nic.ngo.        **172800**    IN    A    199.249.120.1|b0.nic.ngo.        **518400**    IN    AAAA    2001:500:c:0:0:0:0:1|
|b2.nic.ngo.        **172800**    IN    AAAA    2001:500:48:0:0:0:0:1|b2.nic.ngo.        **518400**    IN    A    199.249.120.1|
|c0.nic.ngo.        **172800**    IN    A    199.19.53.1|b2.nic.ngo.        **518400**    IN    AAAA    2001:500:48:0:0:0:0:1|
|c0.nic.ngo.        **172800**    IN    AAAA    2001:500:b:0:0:0:0:1|c0.nic.ngo.        **518400**    IN    A    199.19.53.1|
|d0.nic.ngo.        **172800**    IN    A    199.19.57.1|c0.nic.ngo.        **518400**    IN    AAAA    2001:500:b:0:0:0:0:1|
|d0.nic.ngo.        **172800**    IN    AAAA    2001:500:f:0:0:0:0:1|d0.nic.ngo.        **518400**    IN    A    199.19.57.1|
||d0.nic.ngo.        **518400**    IN    AAAA    2001:500:f:0:0:0:0:1|
#
## xn--wgbl6a
|expected|actual|
|--------|---|
|a.registry.qa.        **172800**    IN    A    178.23.16.104|a.registry.qa.        **518400**    IN    A    178.23.16.104|
|b.registry.qa.        **172800**    IN    A    178.23.17.104|b.registry.qa.        **518400**    IN    A    178.23.17.104|
|c.registry.qa.        **172800**    IN    A    212.77.192.10|c.registry.qa.        **518400**    IN    A    212.77.192.10|
|d.registry.qa.        **172800**    IN    A    212.77.192.13|d.registry.qa.        **518400**    IN    A    212.77.192.13|
|e.registry.qa.        **172800**    IN    A    178.23.20.60|e.registry.qa.        **518400**    IN    A    178.23.20.60|
|f.registry.qa.        **172800**    IN    **A**    **37.209.192.6**|f.registry.qa.        **518400**    IN    **AAAA**    **2001:dcd:1:0:0:0:0:6**|
|f.registry.qa.        **172800**    IN    **AAAA**    **2001:dcd:1:0:0:0:0:6**|f.registry.qa.        **518400**    IN    **A**    **37.209.192.6**|
|g.registry.qa.        **172800**    IN    A    37.209.194.6|g.registry.qa.        **518400**    IN    A    37.209.194.6|
|g.registry.qa.        **172800**    IN    AAAA    2001:dcd:2:0:0:0:0:6|g.registry.qa.        **518400**    IN    AAAA    2001:dcd:2:0:0:0:0:6|
|h.registry.qa.        **172800**    IN    A    178.23.22.60|h.registry.qa.        **518400**    IN    A    178.23.22.60|
|**h**.registry.qa.        **172800**    IN    AAAA    **2a0c:a640:1:22:0:0:0:60**|**i**.registry.qa.        **518400**    IN    AAAA    **2001:500:14:6062:ad:0:0:1**|
|i.registry.qa.        **172800**    IN    A    204.61.216.62|i.registry.qa.        **518400**    IN    A    204.61.216.62|
|**i.registry.qa.        172800    IN    AAAA    2001:500:14:6062:ad:0:0:1**||
#
## crs
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bofa
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## marriott
|expected|actual|
|--------|---|
|**marriott.        86400    IN    DS    18181 7 2 C32ED1F3444223C84A352C0EB765B8DAD456A01C7E49ECB4A6484790626D78B0**||
|a0.nic.marriott.    **172800**    IN    A    65.22.236.9|a0.nic.marriott.    **518400**    IN    A    65.22.236.9|
|a0.nic.marriott.    **172800**    IN    AAAA    2a01:8840:e6:0:0:0:0:9|a0.nic.marriott.    **518400**    IN    AAAA    2a01:8840:e6:0:0:0:0:9|
|a2.nic.marriott.    **172800**    IN    **A**    **65.22.239.9**|a2.nic.marriott.    **518400**    IN    **AAAA**    **2a01:8840:e9:0:0:0:0:9**|
|a2.nic.marriott.    **172800**    IN    **AAAA**    **2a01:8840:e9:0:0:0:0:9**|a2.nic.marriott.    **518400**    IN    **A**    **65.22.239.9**|
|b0.nic.marriott.    **172800**    IN    A    65.22.237.9|b0.nic.marriott.    **518400**    IN    A    65.22.237.9|
|b0.nic.marriott.    **172800**    IN    AAAA    2a01:8840:e7:0:0:0:0:9|b0.nic.marriott.    **518400**    IN    AAAA    2a01:8840:e7:0:0:0:0:9|
|c0.nic.marriott.    **172800**    IN    A    65.22.238.9|c0.nic.marriott.    **518400**    IN    A    65.22.238.9|
|c0.nic.marriott.    **172800**    IN    AAAA    2a01:8840:e8:0:0:0:0:9|c0.nic.marriott.    **518400**    IN    AAAA    2a01:8840:e8:0:0:0:0:9|
#
## csc
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## lds
|expected|actual|
|--------|---|
|lds.            86400    IN    DS    **36055** **8** 2 **CD5AC0CB52D71DC6D369CC4CCA8AAD970690BCF3BC33F2202890668E47D34A5A**|lds.            86400    IN    DS    **934** **7** **1 B24B8B815C37C6448C2603F4D9AE6301C3A817B2**|
|a0.nic.lds.        **172800**    IN    A    65.22.152.9|**lds.            86400    IN    DS    934 7 **2 **BE4AFC3ACFD9C657F3D3BD3EED892EE356E17FCB5DF287E3755797EB66B28C21**|
|a0.nic.lds.        **172800**    IN    AAAA    2a01:8840:96:0:0:0:0:9|a0.nic.lds.        **518400**    IN    A    65.22.152.9|
|a2.nic.lds.        **172800**    IN    A    65.22.155.9|a0.nic.lds.        **518400**    IN    AAAA    2a01:8840:96:0:0:0:0:9|
|a2.nic.lds.        **172800**    IN    AAAA    2a01:8840:99:0:0:0:0:9|a2.nic.lds.        **518400**    IN    A    65.22.155.9|
|b0.nic.lds.        **172800**    IN    A    65.22.153.9|a2.nic.lds.        **518400**    IN    AAAA    2a01:8840:99:0:0:0:0:9|
|b0.nic.lds.        **172800**    IN    AAAA    2a01:8840:97:0:0:0:0:9|b0.nic.lds.        **518400**    IN    A    65.22.153.9|
|c0.nic.lds.        **172800**    IN    A    65.22.154.9|b0.nic.lds.        **518400**    IN    AAAA    2a01:8840:97:0:0:0:0:9|
|c0.nic.lds.        **172800**    IN    AAAA    2a01:8840:98:0:0:0:0:9|c0.nic.lds.        **518400**    IN    A    65.22.154.9|
||c0.nic.lds.        **518400**    IN    AAAA    2a01:8840:98:0:0:0:0:9|
#
## aol
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## statebank
|expected|actual|
|--------|---|
|statebank.        86400    IN    DS    **6556** **8** **2** **CEF021E759C80743AC2B871F39DB1AAC7BFB542244B74EBD5C98776F5D4D844A**|statebank.        86400    IN    DS    **23235** **7** **1** **F81317706CD1FB277ECE0582C1FB1369C1B9FA94**|
|**a0.nic.**statebank.    **172800**    IN    **A**    **65.22.176.1**|statebank.        **86400**    IN    **DS**    **23235** **7 2 E2E22D92C1B8AD2F0CC366A43A4A2D51986C1D625C631063CBC5B73CDBB5D953**|
|a0.nic.statebank.    **172800**    IN    AAAA    2a01:8840:aa:0:0:0:0:1|a0.nic.statebank.    **518400**    IN    AAAA    2a01:8840:aa:0:0:0:0:1|
|**a2**.nic.statebank.    **172800**    IN    A    65.22.**179**.1|**a0**.nic.statebank.    **518400**    IN    A    65.22.**176**.1|
|a2.nic.statebank.    **172800**    IN    AAAA    2a01:8840:ad:0:0:0:0:1|a2.nic.statebank.    **518400**    IN    AAAA    2a01:8840:ad:0:0:0:0:1|
|**b0**.nic.statebank.    **172800**    IN    A    65.22.**177**.1|**a2**.nic.statebank.    **518400**    IN    A    65.22.**179**.1|
|b0.nic.statebank.    **172800**    IN    AAAA    2a01:8840:ab:0:0:0:0:1|b0.nic.statebank.    **518400**    IN    AAAA    2a01:8840:ab:0:0:0:0:1|
|**c0**.nic.statebank.    **172800**    IN    A    65.22.**178**.1|**b0**.nic.statebank.    **518400**    IN    A    65.22.**177**.1|
|c0.nic.statebank.    **172800**    IN    AAAA    2a01:8840:ac:0:0:0:0:1|c0.nic.statebank.    **518400**    IN    AAAA    2a01:8840:ac:0:0:0:0:1|
||**c0.nic.statebank.    518400    IN    A    65.22.178.1**|
#
## hotmail
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## nowruz
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|ns.cocca.fr.        **518400**    IN    **A**    **185**.**17.236.123**|
|**a**.ns.**nic**.**nowruz**.    **172800**    IN    **A**    **72.0.49.10**|ns.**cocca**.**fr**.        **518400**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|
|a.ns.nic.nowruz.    **172800**    IN    AAAA    2620:171:a01:ad:0:0:0:10|a.ns.nic.nowruz.    **518400**    IN    AAAA    2620:171:a01:ad:0:0:0:10|
|**b**.ns.nic.nowruz.    **172800**    IN    A    72.**42**.**113**.10|**a**.ns.nic.nowruz.    **518400**    IN    A    72.**0**.**49**.10|
|b.ns.nic.nowruz.    **172800**    IN    AAAA    2620:171:d01:dc:0:0:0:10|b.ns.nic.nowruz.    **518400**    IN    AAAA    2620:171:d01:dc:0:0:0:10|
||**b.ns.nic.nowruz.    518400    IN    A    72.42.113.10**|
#
## walmart
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--pssy2u
|expected|actual|
|--------|---|
|**xn--pssy2u.        86400    IN    DS    39624 8 2 C8ACA8ACBFAF0BBABF83AD3A480DF9E961364D1BF326C953F1CF9597E844C95B**||
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|**xn--pssy2u.        86400    IN    DS    39624 8 2 C8ACA8ACBFAF0BBABF83AD3A480DF9E961364D1BF326C953F1CF9597E844C95B**|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
#
## gallo
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## java
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## wolterskluwer
|expected|actual|
|--------|---|
|wolterskluwer.        86400    IN    DS    **58234** **8** 2 **97DCE05D28C78AF0B76524DF031D5FAD0E1901B5AE12515BE48FC758AF56E473**|wolterskluwer.        86400    IN    DS    **46705** **7** **1 3FB2F5953F5DC83E35D8468980CA4F680699C1D2**|
|a0.nic.wolterskluwer.    **172800**    IN    A    65.22.204.25|**wolterskluwer.        86400    IN    DS    46705 7 **2 **81C1C9504E49E199F0CAB91C3EDF206A89C0F1D487099486E49F7AA31DE8B050**|
|a0.nic.wolterskluwer.    **172800**    IN    AAAA    2a01:8840:c6:0:0:0:0:25|a0.nic.wolterskluwer.    **518400**    IN    A    65.22.204.25|
|a2.nic.wolterskluwer.    **172800**    IN    **A**    **65.22.207.25**|a0.nic.wolterskluwer.    **518400**    IN    AAAA    2a01:8840:c6:0:0:0:0:25|
|a2.nic.wolterskluwer.    **172800**    IN    **AAAA**    **2a01:8840:c9:0:0:0:0:25**|a2.nic.wolterskluwer.    **518400**    IN    **AAAA**    **2a01:8840:c9:0:0:0:0:25**|
|b0.nic.wolterskluwer.    **172800**    IN    A    65.22.205.25|a2.nic.wolterskluwer.    **518400**    IN    **A**    **65.22.207.25**|
|b0.nic.wolterskluwer.    **172800**    IN    AAAA    2a01:8840:c7:0:0:0:0:25|b0.nic.wolterskluwer.    **518400**    IN    A    65.22.205.25|
|c0.nic.wolterskluwer.    **172800**    IN    A    65.22.206.25|b0.nic.wolterskluwer.    **518400**    IN    AAAA    2a01:8840:c7:0:0:0:0:25|
|c0.nic.wolterskluwer.    **172800**    IN    AAAA    2a01:8840:c8:0:0:0:0:25|c0.nic.wolterskluwer.    **518400**    IN    A    65.22.206.25|
||c0.nic.wolterskluwer.    **518400**    IN    AAAA    2a01:8840:c8:0:0:0:0:25|
#
## shia
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|ns.cocca.fr.        **518400**    IN    **A**    **185**.**17.236.123**|
|**a**.ns.**nic**.**shia**.        **172800**    IN    **A**    **72.0.49.7**|ns.**cocca**.**fr**.        **518400**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|
|a.ns.nic.shia.        **172800**    IN    AAAA    2620:171:a01:ad:0:0:0:7|a.ns.nic.shia.        **518400**    IN    AAAA    2620:171:a01:ad:0:0:0:7|
|**b**.ns.nic.shia.        **172800**    IN    A    72.**42**.**113**.7|**a**.ns.nic.shia.        **518400**    IN    A    72.**0**.**49**.7|
|b.ns.nic.shia.        **172800**    IN    AAAA    2620:171:d01:dc:0:0:0:7|b.ns.nic.shia.        **518400**    IN    AAAA    2620:171:d01:dc:0:0:0:7|
||**b.ns.nic.shia.        518400    IN    A    72.42.113.7**|
#
## press
|expected|actual|
|--------|---|
|press.            172800    IN    NS    **e**.nic.press.|press.            172800    IN    NS    **c**.nic.press.|
|press.            172800    IN    NS    **f**.nic.press.|press.            172800    IN    NS    **d**.nic.press.|
|a.nic.press.        **172800**    IN    **A**    **194.169.218.34**|a.nic.press.        **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:34**|
|a.nic.press.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:34**|a.nic.press.        **518400**    IN    **A**    **194.169.218.34**|
|b.nic.press.        **172800**    IN    A    185.24.64.34|b.nic.press.        **518400**    IN    A    185.24.64.34|
|b.nic.press.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:34|b.nic.press.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:34|
|**e**.nic.press.        **172800**    IN    A    **212**.**18**.**248**.**34**|**c**.nic.press.        **518400**    IN    A    **185**.**38**.**99**.**3**|
|**e**.nic.press.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:34**|**c**.nic.press.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:3**|
|**f**.nic.press.        **172800**    IN    A    **212**.**18**.**249**.**34**|**d**.nic.press.        **518400**    IN    A    **108**.**59**.**161**.**3**|
|**f**.nic.press.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:34**|**d**.nic.press.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:3**|
#
## pnc
|expected|actual|
|--------|---|
|pnc.            86400    IN    DS    **40264** **8** 2 **137C7B7B6BE3D79FF1C7F5DDB9525CD8BF14B821DCEC08FF5A3A7B128E58660B**|pnc.            86400    IN    DS    **54006** **7** **1 615F82A68B6EC43597CF64B429549D5529B2B4A4**|
|a0.nic.pnc.        **172800**    IN    **A**    **65.22.64.25**|**pnc.            86400    IN    DS    54006 7 **2 **ED3F8476AD8C82B1B2D0B29CD5B9AF7A1654732C77748AE6EC5DDF6CCCC19ADB**|
|a0.nic.pnc.        **172800**    IN    **AAAA**    **2a01:8840:3e:0:0:0:0:25**|a0.nic.pnc.        **518400**    IN    **AAAA**    **2a01:8840:3e:0:0:0:0:25**|
|a2.nic.pnc.        **172800**    IN    A    65.22.67.25|a0.nic.pnc.        **518400**    IN    **A**    **65.22.64.25**|
|a2.nic.pnc.        **172800**    IN    AAAA    2a01:8840:41:0:0:0:0:25|a2.nic.pnc.        **518400**    IN    A    65.22.67.25|
|b0.nic.pnc.        **172800**    IN    A    65.22.65.25|a2.nic.pnc.        **518400**    IN    AAAA    2a01:8840:41:0:0:0:0:25|
|b0.nic.pnc.        **172800**    IN    AAAA    2a01:8840:3f:0:0:0:0:25|b0.nic.pnc.        **518400**    IN    A    65.22.65.25|
|c0.nic.pnc.        **172800**    IN    A    65.22.66.25|b0.nic.pnc.        **518400**    IN    AAAA    2a01:8840:3f:0:0:0:0:25|
|c0.nic.pnc.        **172800**    IN    AAAA    2a01:8840:40:0:0:0:0:25|c0.nic.pnc.        **518400**    IN    A    65.22.66.25|
||c0.nic.pnc.        **518400**    IN    AAAA    2a01:8840:40:0:0:0:0:25|
#
## juniper
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--fzys8d69uvgm
|expected|actual|
|--------|---|
|xn--fzys8d69uvgm.    86400    IN    DS    **5302** **8** 2 **1D8B69A4FCFC475FB7D9D7B5B1366B92C51826A503A530F2EA1C6D07D58B9D2A**|xn--fzys8d69uvgm.    86400    IN    DS    **54556** **7** **1 B20CF58A31D06D347DFA35EA82405584AF194932**|
|a0.nic.xn--fzys8d69uvgm.    **172800**    IN    **A**    **65.22.172.33**|**xn--fzys8d69uvgm.    86400    IN    DS    54556 7 **2 **EB9DD82DD06ED607B443E885FF60C65606555BE2D9701C2F39133B11B53122AC**|
|a0.nic.xn--fzys8d69uvgm.    **172800**    IN    **AAAA**    **2a01:8840:a6:0:0:0:0:33**|a0.nic.xn--fzys8d69uvgm.    **518400**    IN    **AAAA**    **2a01:8840:a6:0:0:0:0:33**|
|a2.nic.xn--fzys8d69uvgm.    **172800**    IN    A    65.22.175.33|a0.nic.xn--fzys8d69uvgm.    **518400**    IN    **A**    **65.22.172.33**|
|a2.nic.xn--fzys8d69uvgm.    **172800**    IN    AAAA    2a01:8840:a9:0:0:0:0:33|a2.nic.xn--fzys8d69uvgm.    **518400**    IN    A    65.22.175.33|
|b0.nic.xn--fzys8d69uvgm.    **172800**    IN    **A**    **65.22.173.33**|a2.nic.xn--fzys8d69uvgm.    **518400**    IN    AAAA    2a01:8840:a9:0:0:0:0:33|
|b0.nic.xn--fzys8d69uvgm.    **172800**    IN    **AAAA**    **2a01:8840:a7:0:0:0:0:33**|b0.nic.xn--fzys8d69uvgm.    **518400**    IN    **AAAA**    **2a01:8840:a7:0:0:0:0:33**|
|c0.nic.xn--fzys8d69uvgm.    **172800**    IN    A    65.22.174.33|b0.nic.xn--fzys8d69uvgm.    **518400**    IN    **A**    **65.22.173.33**|
|c0.nic.xn--fzys8d69uvgm.    **172800**    IN    AAAA    2a01:8840:a8:0:0:0:0:33|c0.nic.xn--fzys8d69uvgm.    **518400**    IN    A    65.22.174.33|
||c0.nic.xn--fzys8d69uvgm.    **518400**    IN    AAAA    2a01:8840:a8:0:0:0:0:33|
#
## cern
|expected|actual|
|--------|---|
|cern.            86400    IN    DS    **20371** **8** **2** **5A48EAB25C4CF4978949D677C182876C48A6C5B7E2282926A954E8E9C8BEC393**|cern.            86400    IN    DS    **63043** **7** **1** **C4095A121939E6E0B2000850F63010CE003F1907**|
|**a0.nic.**cern.        **172800**    IN    **A**    **65.22.224.1**|cern.            **86400**    IN    **DS**    **63043** **7 2 61E362B956DC54FFFAAD2A41B5F81B2967FEBACF39AE1BCB78A8FA76699FFC0F**|
|a0.nic.cern.        **172800**    IN    AAAA    2a01:8840:da:0:0:0:0:1|a0.nic.cern.        **518400**    IN    AAAA    2a01:8840:da:0:0:0:0:1|
|**a2**.nic.cern.        **172800**    IN    A    65.22.**227**.1|**a0**.nic.cern.        **518400**    IN    A    65.22.**224**.1|
|a2.nic.cern.        **172800**    IN    AAAA    2a01:8840:dd:0:0:0:0:1|a2.nic.cern.        **518400**    IN    AAAA    2a01:8840:dd:0:0:0:0:1|
|b0.nic.cern.        **172800**    IN    A    65.22.225.1|**a2.nic.cern.        518400    IN    A    65.22.227.1**|
|b0.nic.cern.        **172800**    IN    AAAA    2a01:8840:db:0:0:0:0:1|b0.nic.cern.        **518400**    IN    A    65.22.225.1|
|c0.nic.cern.        **172800**    IN    **A**    **65.22.226.1**|b0.nic.cern.        **518400**    IN    AAAA    2a01:8840:db:0:0:0:0:1|
|c0.nic.cern.        **172800**    IN    **AAAA**    **2a01:8840:dc:0:0:0:0:1**|c0.nic.cern.        **518400**    IN    **AAAA**    **2a01:8840:dc:0:0:0:0:1**|
||c0.nic.cern.        **518400**    IN    **A**    **65.22.226.1**|
#
## tvs
|expected|actual|
|--------|---|
|tvs.            86400    IN    DS    **29161** **8** 2 **A36CBB75C2C810D16FDD5562C334351BDD007F5AEB008537115586951AC39240**|tvs.            86400    IN    DS    **9544** **7** **1 576F18D90579172AE7739828C581643731B2D3BE**|
|a0.nic.tvs.        **172800**    IN    **A**    **65.22.204.9**|**tvs.            86400    IN    DS    9544 7 **2 **72FAD7B3803609421622C1B13C877C2AC7A5A1009F835F39A267414B82E155D2**|
|a0.nic.tvs.        **172800**    IN    **AAAA**    **2a01:8840:c6:0:0:0:0:9**|a0.nic.tvs.        **518400**    IN    **AAAA**    **2a01:8840:c6:0:0:0:0:9**|
|a2.nic.tvs.        **172800**    IN    A    65.22.207.9|a0.nic.tvs.        **518400**    IN    **A**    **65.22.204.9**|
|a2.nic.tvs.        **172800**    IN    AAAA    2a01:8840:c9:0:0:0:0:9|a2.nic.tvs.        **518400**    IN    A    65.22.207.9|
|b0.nic.tvs.        **172800**    IN    A    65.22.205.9|a2.nic.tvs.        **518400**    IN    AAAA    2a01:8840:c9:0:0:0:0:9|
|b0.nic.tvs.        **172800**    IN    AAAA    2a01:8840:c7:0:0:0:0:9|b0.nic.tvs.        **518400**    IN    A    65.22.205.9|
|c0.nic.tvs.        **172800**    IN    A    65.22.206.9|b0.nic.tvs.        **518400**    IN    AAAA    2a01:8840:c7:0:0:0:0:9|
|c0.nic.tvs.        **172800**    IN    AAAA    2a01:8840:c8:0:0:0:0:9|c0.nic.tvs.        **518400**    IN    A    65.22.206.9|
||c0.nic.tvs.        **518400**    IN    AAAA    2a01:8840:c8:0:0:0:0:9|
#
## wang
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## jprs
|expected|actual|
|--------|---|
|jprs.            86400    IN    DS    **64396** 8 2 **5470EDA9FD99D547C78D9A6B05AA7BEB61B53F9DD56D7EC2512C1234C468D983**|jprs.            86400    IN    DS    **26554** 8 2 **A52A8155ADE612B2C610171984751F05D18E5CF46A57D5DEA88E484BCD3B7E5D**|
|tld1.nic.jprs.        **172800**    IN    A    103.47.2.1|tld1.nic.jprs.        **518400**    IN    A    103.47.2.1|
|tld1.nic.jprs.        **172800**    IN    AAAA    2001:dda:0:0:0:0:0:1|tld1.nic.jprs.        **518400**    IN    AAAA    2001:dda:0:0:0:0:0:1|
|tld2.nic.jprs.        **172800**    IN    **A**    **117.104.133.16**|tld2.nic.jprs.        **518400**    IN    **AAAA**    **2001:218:3001:0:0:0:0:1**|
|tld2.nic.jprs.        **172800**    IN    **AAAA**    **2001:218:3001:0:0:0:0:1**|tld2.nic.jprs.        **518400**    IN    **A**    **117.104.133.16**|
|tld3.nic.jprs.        **172800**    IN    A    65.22.40.1|tld3.nic.jprs.        **518400**    IN    A    65.22.40.1|
|tld3.nic.jprs.        **172800**    IN    AAAA    2a01:8840:1ba:0:0:0:0:1|tld3.nic.jprs.        **518400**    IN    AAAA    2a01:8840:1ba:0:0:0:0:1|
|tld4.nic.jprs.        **172800**    IN    A    103.198.210.1|tld4.nic.jprs.        **518400**    IN    A    103.198.210.1|
|tld4.nic.jprs.        **172800**    IN    AAAA    2403:2880:0:0:0:0:0:1|tld4.nic.jprs.        **518400**    IN    AAAA    2403:2880:0:0:0:0:0:1|
|tld5.nic.jprs.        **172800**    IN    A    65.22.40.129|tld5.nic.jprs.        **518400**    IN    A    65.22.40.129|
|tld5.nic.jprs.        **172800**    IN    AAAA    2a01:8840:1ba:0:0:0:0:129|tld5.nic.jprs.        **518400**    IN    AAAA    2a01:8840:1ba:0:0:0:0:129|
#
## onyourside
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## arte
|expected|actual|
|--------|---|
|**arte.            86400    IN    DS    46728 8 2 D197248E95610371F7624D79D397037EA5E200E6F338BCCEDF5E93BB68448152**||
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|**arte.            86400    IN    DS    46728 8 2 D197248E95610371F7624D79D397037EA5E200E6F338BCCEDF5E93BB68448152**|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
#
## weibo
|expected|actual|
|--------|---|
|weibo.            86400    IN    DS    **40642** **8** 2 **930EDCD3B0036BCDEBF43862AD49F6B7486DFECFC2E42F769AB66F21938CF112**|weibo.            86400    IN    DS    **48381** **7** **1 25267F578DD92971BAB8D4C78D994EF95FAEEDF4**|
|a0.nic.weibo.        **172800**    IN    A    65.22.56.41|**weibo.            86400    IN    DS    48381 7 **2 **5794FAEB90DD944D20C1D1A989AC7EB97FD8D72EC457780DC8A2411E128ECEA9**|
|a0.nic.weibo.        **172800**    IN    AAAA    2a01:8840:36:0:0:0:0:41|a0.nic.weibo.        **518400**    IN    A    65.22.56.41|
|a2.nic.weibo.        **172800**    IN    A    65.22.59.41|a0.nic.weibo.        **518400**    IN    AAAA    2a01:8840:36:0:0:0:0:41|
|**a2**.nic.weibo.        **172800**    IN    AAAA    **2a01:8840:39:0:0:0:0:41**|a2.nic.weibo.        **518400**    IN    **AAAA    2a01:8840:39:0:0:0:0:41**|
|b0.nic.weibo.        **172800**    IN    A    65.22.57.41|**a2.nic.weibo.        518400    IN    **A    65.22.59.41|
|**b0**.nic.weibo.        **172800**    IN    AAAA    **2a01:8840:37:0:0:0:0:41**|**b0**.nic.weibo.        **518400**    IN    AAAA    **2a01:8840:37:0:0:0:0:41**|
|c0.nic.weibo.        **172800**    IN    A    65.22.58.41|b0.nic.weibo.        **518400**    IN    A    65.22.57.41|
|**c0.nic.weibo.        172800    IN    AAAA    2a01:8840:38:0:0:0:0:41**|**c0**.nic.weibo.        **518400**    IN    AAAA    **2a01:8840:38:0:0:0:0:41**|
||c0.nic.weibo.        **518400**    IN    A    65.22.58.41|
#
## richardli
|expected|actual|
|--------|---|
|richardli.        86400    IN    DS    **41074** **8** 2 **FF2E8B0F81588F0266003EB8AC2D8617607069C425DDE1BB7734FCC4F93C8D88**|richardli.        86400    IN    DS    **60340** **7** **1 2E3E96F08CC10EDFF8287B0B01916222455079ED**|
|a0.nic.richardli.    **172800**    IN    **A**    **65.22.136.33**|**richardli.        86400    IN    DS    60340 7 **2 **37020C36172B3961EFF1111EE7D1DDDAD08E89BF10245DB24AB2C0C75E4C37E7**|
|a0.nic.richardli.    **172800**    IN    **AAAA**    **2a01:8840:86:0:0:0:0:33**|a0.nic.richardli.    **518400**    IN    **AAAA**    **2a01:8840:86:0:0:0:0:33**|
|a2.nic.richardli.    **172800**    IN    A    65.22.139.33|a0.nic.richardli.    **518400**    IN    **A**    **65.22.136.33**|
|a2.nic.richardli.    **172800**    IN    AAAA    2a01:8840:89:0:0:0:0:33|a2.nic.richardli.    **518400**    IN    A    65.22.139.33|
|b0.nic.richardli.    **172800**    IN    A    65.22.137.33|a2.nic.richardli.    **518400**    IN    AAAA    2a01:8840:89:0:0:0:0:33|
|b0.nic.richardli.    **172800**    IN    AAAA    2a01:8840:87:0:0:0:0:33|b0.nic.richardli.    **518400**    IN    A    65.22.137.33|
|c0.nic.richardli.    **172800**    IN    A    65.22.138.33|b0.nic.richardli.    **518400**    IN    AAAA    2a01:8840:87:0:0:0:0:33|
|c0.nic.richardli.    **172800**    IN    AAAA    2a01:8840:88:0:0:0:0:33|c0.nic.richardli.    **518400**    IN    A    65.22.138.33|
||c0.nic.richardli.    **518400**    IN    AAAA    2a01:8840:88:0:0:0:0:33|
#
## xn--nqv7f
|expected|actual|
|--------|---|
|xn--nqv7f.        86400    IN    DS    **22459** **8** 2 **435A53C55E065976A2C03F1D8B09241A6EC3EA90D63D6CDAECD0ED93DAF61E99**|xn--nqv7f.        86400    IN    DS    **48928** **7** **1 8034A486A658ABAEB86C46399D42F37E52B74249**|
|a0.nic.xn--nqv7f.    **172800**    IN    A    65.22.184.17|**xn--nqv7f.        86400    IN    DS    48928 7 **2 **735851450CC762E7B884F6340A4A8ABB3D2485DF65FD8C5F32D9C193FC016A22**|
|a0.nic.xn--nqv7f.    **172800**    IN    AAAA    2a01:8840:b2:0:0:0:0:17|a0.nic.xn--nqv7f.    **518400**    IN    A    65.22.184.17|
|a2.nic.xn--nqv7f.    **172800**    IN    A    65.22.187.17|a0.nic.xn--nqv7f.    **518400**    IN    AAAA    2a01:8840:b2:0:0:0:0:17|
|a2.nic.xn--nqv7f.    **172800**    IN    AAAA    2a01:8840:b5:0:0:0:0:17|a2.nic.xn--nqv7f.    **518400**    IN    A    65.22.187.17|
|b0.nic.xn--nqv7f.    **172800**    IN    A    65.22.185.17|a2.nic.xn--nqv7f.    **518400**    IN    AAAA    2a01:8840:b5:0:0:0:0:17|
|b0.nic.xn--nqv7f.    **172800**    IN    AAAA    2a01:8840:b3:0:0:0:0:17|b0.nic.xn--nqv7f.    **518400**    IN    A    65.22.185.17|
|c0.nic.xn--nqv7f.    **172800**    IN    A    65.22.186.17|b0.nic.xn--nqv7f.    **518400**    IN    AAAA    2a01:8840:b3:0:0:0:0:17|
|c0.nic.xn--nqv7f.    **172800**    IN    AAAA    2a01:8840:b4:0:0:0:0:17|c0.nic.xn--nqv7f.    **518400**    IN    A    65.22.186.17|
||c0.nic.xn--nqv7f.    **518400**    IN    AAAA    2a01:8840:b4:0:0:0:0:17|
#
## foodnetwork
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xbox
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## broker
|expected|actual|
|--------|---|
|broker.            172800    IN    NS    **a**.**nic**.**broker**.|broker.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|broker.            172800    IN    NS    **b**.**nic**.**broker**.|broker.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|broker.            172800    IN    NS    **c**.**nic**.**broker**.|broker.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|broker.            172800    IN    NS    **d**.**nic**.**broker**.|broker.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**broker.            86400    IN    DS    5014 8 2 0A9E9B603587514C3CC37BB970C35F6C6FB02F62D267C523734EC7F7E61651E2**||
|**a**.**nic**.**broker**.        **172800**    IN    A    **194**.**169**.**218**.**121**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**broker**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:121**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**b.nic.broker.        172800    IN    **A    **185**.**24**.**64**.**121**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b**.**nic**.**broker**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:121**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**c**.**nic**.**broker**.        **172800**    IN    A    **212**.**18**.**248**.**121**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**broker**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:121**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**d**.**nic**.**broker**.        **172800**    IN    **A**    **212.18.249.121**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**broker**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:121**||
#
## aarp
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--45q11c
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## macys
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## hdfc
|expected|actual|
|--------|---|
|hdfc.            86400    IN    DS    **23122** **8** 2 **F73544D186EF971C4E3172EDDD985D4579C4BB60B5D04396921D25FF9095DC6A**|hdfc.            86400    IN    DS    **43104** **7** **1 D53CED9832799749B3F2F2FF07F67EDADF63396C**|
|a0.nic.hdfc.        **172800**    IN    A    65.22.176.33|**hdfc.            86400    IN    DS    43104 7 **2 **8AEF49234BC4A9AB6557840E6A731BDCE5EB03ECCB6265F149B2EB9644A35D37**|
|a0.nic.hdfc.        **172800**    IN    AAAA    2a01:8840:aa:0:0:0:0:33|a0.nic.hdfc.        **518400**    IN    A    65.22.176.33|
|a2.nic.hdfc.        **172800**    IN    A    65.22.179.33|a0.nic.hdfc.        **518400**    IN    AAAA    2a01:8840:aa:0:0:0:0:33|
|a2.nic.hdfc.        **172800**    IN    AAAA    2a01:8840:ad:0:0:0:0:33|a2.nic.hdfc.        **518400**    IN    A    65.22.179.33|
|b0.nic.hdfc.        **172800**    IN    A    65.22.177.33|a2.nic.hdfc.        **518400**    IN    AAAA    2a01:8840:ad:0:0:0:0:33|
|b0.nic.hdfc.        **172800**    IN    AAAA    2a01:8840:ab:0:0:0:0:33|b0.nic.hdfc.        **518400**    IN    A    65.22.177.33|
|c0.nic.hdfc.        **172800**    IN    A    65.22.178.33|b0.nic.hdfc.        **518400**    IN    AAAA    2a01:8840:ab:0:0:0:0:33|
|c0.nic.hdfc.        **172800**    IN    AAAA    2a01:8840:ac:0:0:0:0:33|c0.nic.hdfc.        **518400**    IN    A    65.22.178.33|
||c0.nic.hdfc.        **518400**    IN    AAAA    2a01:8840:ac:0:0:0:0:33|
#
## voting
|expected|actual|
|--------|---|
|voting.            172800    IN    NS    a.nic.voting.|voting.            172800    IN    NS    a.**dns.**nic.voting.|
|voting.            172800    IN    NS    **b**.nic.voting.|voting.            172800    IN    NS    **m**.**dns.**nic.voting.|
|voting.            172800    IN    NS    **c**.nic.voting.|voting.            172800    IN    NS    **n**.**dns.**nic.voting.|
|voting.            **172800**    IN    **NS**    **d.nic.voting.**|voting.            **86400**    IN    **DS**    **51755 8 2 C65CB6885D44EF372400824799D8D6731E52DCA6711CD1F7840329D49DC74E9A**|
|**voting.            86400    IN    DS    51755 8 2 C65CB6885D44EF372400824799D8D6731E52DCA6711CD1F7840329D49DC74E9A**|a.**dns.**nic.voting.    **518400**    IN    A    **194**.**0**.**25**.**17**|
|a.nic.voting.        **172800**    IN    A    **37**.**209**.**192**.**10**|a.**dns.**nic.voting.    **518400**    IN    AAAA    **2001:678:20:0:0:0:0:17**|
|a.nic.voting.        **172800**    IN    AAAA    **2001:dcd:1:0:0:0:0:10**|**m**.**dns.**nic.voting.    **518400**    IN    A    **194**.**0**.**26**.**6**|
|**b**.nic.voting.        **172800**    IN    A    **37**.**209**.**194**.**10**|**m**.**dns.**nic.voting.    **518400**    IN    AAAA    **2001:67c:10e0:0:0:0:0:6**|
|**b**.nic.voting.        **172800**    IN    AAAA    **2001:dcd:2:0:0:0:0:10**|**n**.**dns**.nic.voting.    **518400**    IN    AAAA    **2001:678:24:0:0:0:0:6**|
|**c**.**nic**.**voting.        172800    IN    A    37.209.196.10**|**n**.**dns.**nic.voting.    **518400**    IN    A    **194**.**0**.**24**.**6**|
|**c.**nic.voting.        **172800**    IN    AAAA    **2001:dcd:3:0:0:0:0:10**||
|**d**.nic.voting.        **172800**    IN    A    **37**.**209**.**198**.**10**||
|**d.nic.voting.        172800    IN    AAAA    2001:dcd:4:0:0:0:0:10**||
#
## microsoft
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## realtor
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## homes
|expected|actual|
|--------|---|
|**homes.            86400    IN    DS    8718 7 2 0EBA92F72451E137CEE7DF3632417BA63FE783BEBCB2AD1650C3A1A237055BDF**||
|a0.nic.homes.        **172800**    IN    A    65.22.100.33|a0.nic.homes.        **518400**    IN    **AAAA    2a01:8840:62:0:0:0:0:33**|
|**a0**.nic.homes.        **172800**    IN    AAAA    **2a01:8840:62:0:0:0:0:33**|**a0.nic.homes.        518400    IN    **A    65.22.100.33|
|a2.nic.homes.        **172800**    IN    A    65.22.103.33|**a2**.nic.homes.        **518400**    IN    AAAA    **2a01:8840:65:0:0:0:0:33**|
|**a2**.nic.homes.        **172800**    IN    AAAA    **2a01:8840:65:0:0:0:0:33**|a2.nic.homes.        **518400**    IN    A    65.22.103.33|
|b0.nic.homes.        **172800**    IN    A    65.22.101.33|**b0**.nic.homes.        **518400**    IN    AAAA    **2a01:8840:63:0:0:0:0:33**|
|**b0**.nic.homes.        **172800**    IN    AAAA    **2a01:8840:63:0:0:0:0:33**|b0.nic.homes.        **518400**    IN    A    65.22.101.33|
|c0.nic.homes.        **172800**    IN    A    65.22.102.33|**c0**.nic.homes.        **518400**    IN    AAAA    **2a01:8840:64:0:0:0:0:33**|
|**c0.nic.homes.        172800    IN    AAAA    2a01:8840:64:0:0:0:0:33**|c0.nic.homes.        **518400**    IN    A    65.22.102.33|
#
## tech
|expected|actual|
|--------|---|
|tech.            172800    IN    NS    **e**.nic.tech.|tech.            172800    IN    NS    **c**.nic.tech.|
|tech.            172800    IN    NS    **f**.nic.tech.|tech.            172800    IN    NS    **d**.nic.tech.|
|a.nic.tech.        **172800**    IN    A    194.169.218.60|a.nic.tech.        **518400**    IN    A    194.169.218.60|
|a.nic.tech.        **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:60|a.nic.tech.        **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:60|
|b.nic.tech.        **172800**    IN    A    185.24.64.60|b.nic.tech.        **518400**    IN    **AAAA    2a04:2b00:13cc:0:0:0:1:60**|
|**b**.nic.tech.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:60**|**b.nic.tech.        518400    IN    **A    185.24.64.60|
|**e**.nic.tech.        **172800**    IN    A    **212**.**18**.**248**.**60**|**c**.nic.tech.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:6**|
|**e**.nic.tech.        **172800**    IN    **AAAA    2a04:2b00:13ee:0:0:0:0:60**|**c**.nic.tech.        **518400**    IN    A    **185**.**38**.**99**.**6**|
|**f.nic.tech.        172800    IN    **A    **212**.**18**.**249**.**60**|**d**.nic.tech.        **518400**    IN    A    **108**.**59**.**161**.**6**|
|**f**.nic.tech.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:60**|**d**.nic.tech.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:6**|
#
## watches
|expected|actual|
|--------|---|
|watches.        **86400**    IN    **DS**    **61699** **8 2 9110905C79B0C95933EB1F037A0D7A150819F1D1553AD89187A7849039A97EBE**|**ns1.dns.nic.**watches.    **518400**    IN    **AAAA**    **2610:a1:1071:0:0:0:1:3a**|
|ns1.dns.nic.watches.    **172800**    IN    A    156.154.169.58|ns1.dns.nic.watches.    **518400**    IN    A    156.154.169.58|
|**ns1.dns.nic.watches.    172800    IN    AAAA    2610:a1:1071:0:0:0:1:3a**|ns2.dns.nic.watches.    **518400**    IN    A    156.154.170.58|
|ns2.dns.nic.watches.    **172800**    IN    A    156.154.170.58|ns2.dns.nic.watches.    **518400**    IN    AAAA    2610:a1:1072:0:0:0:1:3a|
|ns2.dns.nic.watches.    **172800**    IN    AAAA    2610:a1:1072:0:0:0:1:3a|ns3.dns.nic.watches.    **518400**    IN    A    156.154.171.58|
|ns3.dns.nic.watches.    **172800**    IN    A    156.154.171.58|ns3.dns.nic.watches.    **518400**    IN    AAAA    2610:a1:1073:0:0:0:1:3a|
|ns3.dns.nic.watches.    **172800**    IN    AAAA    2610:a1:1073:0:0:0:1:3a|ns4.dns.nic.watches.    **518400**    IN    A    156.154.172.58|
|ns4.dns.nic.watches.    **172800**    IN    A    156.154.172.58|ns4.dns.nic.watches.    **518400**    IN    AAAA    2610:a1:1074:0:0:0:1:3a|
|ns4.dns.nic.watches.    **172800**    IN    AAAA    2610:a1:1074:0:0:0:1:3a|ns5.dns.nic.watches.    **518400**    IN    A    156.154.173.58|
|ns5.dns.nic.watches.    **172800**    IN    A    156.154.173.58|ns5.dns.nic.watches.    **518400**    IN    AAAA    2610:a1:1075:0:0:0:1:3a|
|ns5.dns.nic.watches.    **172800**    IN    AAAA    2610:a1:1075:0:0:0:1:3a|ns6.dns.nic.watches.    **518400**    IN    A    156.154.174.58|
|ns6.dns.nic.watches.    **172800**    IN    A    156.154.174.58|ns6.dns.nic.watches.    **518400**    IN    AAAA    2610:a1:1076:0:0:0:1:3a|
|ns6.dns.nic.watches.    **172800**    IN    AAAA    2610:a1:1076:0:0:0:1:3a||
#
## bloomberg
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## americanfamily
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## boats
|expected|actual|
|--------|---|
|**boats.            86400    IN    DS    62565 7 2 30BEE96FA869DE80EEAB798468BE1CAEC25826F061695DE47B7037268FAB470D**|a0.nic.boats.        **518400**    IN    A    65.22.104.17|
|a0.nic.boats.        **172800**    IN    A    65.22.104.17|a0.nic.boats.        **518400**    IN    AAAA    2a01:8840:66:0:0:0:0:17|
|a0.nic.boats.        **172800**    IN    AAAA    2a01:8840:66:0:0:0:0:17|a2.nic.boats.        **518400**    IN    A    65.22.107.17|
|a2.nic.boats.        **172800**    IN    A    65.22.107.17|a2.nic.boats.        **518400**    IN    AAAA    2a01:8840:69:0:0:0:0:17|
|a2.nic.boats.        **172800**    IN    AAAA    2a01:8840:69:0:0:0:0:17|b0.nic.boats.        **518400**    IN    **AAAA**    **2a01:8840:67:0:0:0:0:17**|
|b0.nic.boats.        **172800**    IN    **A**    **65.22.105.17**|b0.nic.boats.        **518400**    IN    **A**    **65.22.105.17**|
|b0.nic.boats.        **172800**    IN    **AAAA**    **2a01:8840:67:0:0:0:0:17**|c0.nic.boats.        **518400**    IN    A    65.22.106.17|
|c0.nic.boats.        **172800**    IN    A    65.22.106.17|c0.nic.boats.        **518400**    IN    AAAA    2a01:8840:68:0:0:0:0:17|
|c0.nic.boats.        **172800**    IN    AAAA    2a01:8840:68:0:0:0:0:17||
#
## pro
|expected|actual|
|--------|---|
|pro.            86400    IN    DS    **42154** **8** 2 **5A8A58F4E30CDE44A47091488870D109108FF45D42FDFDD30B448D78DFFD5566**|pro.            86400    IN    DS    **47221** **7** **1 00CBFCBDC9C6E659FB2385B3982E93E98D71052D**|
|a0.pro.afilias-nst.info.    **172800**    IN    A    199.182.0.1|**pro.            86400    IN    DS    47221 7 **2 **5A10389E282CB03F1083C1662B218B97CFE61024B991C7C5D8BB5685AD6487CA**|
|a0.pro.afilias-nst.info.    **172800**    IN    AAAA    2001:500:c0:0:0:0:0:1|a0.pro.afilias-nst.info.    **518400**    IN    A    199.182.0.1|
|a2.pro.afilias-nst.info.    **172800**    IN    A    199.182.32.1|a0.pro.afilias-nst.info.    **518400**    IN    AAAA    2001:500:c0:0:0:0:0:1|
|a2.pro.afilias-nst.info.    **172800**    IN    AAAA    2001:500:e0:0:0:0:0:1|a2.pro.afilias-nst.info.    **518400**    IN    A    199.182.32.1|
|c0.pro.afilias-nst.info.    **172800**    IN    A    199.182.16.1|a2.pro.afilias-nst.info.    **518400**    IN    AAAA    2001:500:e0:0:0:0:0:1|
|c0.pro.afilias-nst.info.    **172800**    IN    AAAA    2001:500:d0:0:0:0:0:1|c0.pro.afilias-nst.info.    **518400**    IN    A    199.182.16.1|
|b0.pro.afilias-nst.org.    **172800**    IN    A    199.182.1.1|c0.pro.afilias-nst.info.    **518400**    IN    AAAA    2001:500:d0:0:0:0:0:1|
|**b0**.pro.afilias-nst.org.    **172800**    IN    AAAA    **2001:500:c1:0:0:0:0:1**|b0.pro.afilias-nst.org.    **518400**    IN    **AAAA    2001:500:c1:0:0:0:0:1**|
|b2.pro.afilias-nst.org.    **172800**    IN    A    199.182.40.1|**b0.pro.afilias-nst.org.    518400    IN    **A    199.182.1.1|
|**b2.pro.afilias-nst.org.    172800    IN    AAAA    2001:500:e1:0:0:0:0:1**|**b2**.pro.afilias-nst.org.    **518400**    IN    AAAA    **2001:500:e1:0:0:0:0:1**|
|d0.pro.afilias-nst.org.    **172800**    IN    A    199.182.17.1|b2.pro.afilias-nst.org.    **518400**    IN    A    199.182.40.1|
|d0.pro.afilias-nst.org.    **172800**    IN    AAAA    2001:500:d1:0:0:0:0:1|d0.pro.afilias-nst.org.    **518400**    IN    A    199.182.17.1|
||d0.pro.afilias-nst.org.    **518400**    IN    AAAA    2001:500:d1:0:0:0:0:1|
#
## ubank
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## museum
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## name
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## iveco
|expected|actual|
|--------|---|
|iveco.            86400    IN    DS    **46609** **8** 2 **A27E3339511F70361002C1105DEA6048E05E175D1809EF566C342BE3B4AF4826**|iveco.            86400    IN    DS    **52228** **7** **1 EEE086916966669B8CDB9EB2803D93B20E6012E1**|
|a0.nic.iveco.        **172800**    IN    A    65.22.120.9|**iveco.            86400    IN    DS    52228 7 **2 **25162D8CE8527D237145ECC462475AF54FDB1DA1889C9D9156C6F94719F9F9AD**|
|a0.nic.iveco.        **172800**    IN    AAAA    2a01:8840:76:0:0:0:0:9|a0.nic.iveco.        **518400**    IN    A    65.22.120.9|
|a2.nic.iveco.        **172800**    IN    A    65.22.123.9|a0.nic.iveco.        **518400**    IN    AAAA    2a01:8840:76:0:0:0:0:9|
|a2.nic.iveco.        **172800**    IN    AAAA    2a01:8840:79:0:0:0:0:9|a2.nic.iveco.        **518400**    IN    A    65.22.123.9|
|b0.nic.iveco.        **172800**    IN    A    65.22.121.9|a2.nic.iveco.        **518400**    IN    AAAA    2a01:8840:79:0:0:0:0:9|
|**b0**.nic.iveco.        **172800**    IN    AAAA    **2a01:8840:77:0:0:0:0:9**|b0.nic.iveco.        **518400**    IN    **AAAA    2a01:8840:77:0:0:0:0:9**|
|c0.nic.iveco.        **172800**    IN    A    65.22.122.9|**b0.nic.iveco.        518400    IN    **A    65.22.121.9|
|**c0.nic.iveco.        172800    IN    AAAA    2a01:8840:78:0:0:0:0:9**|**c0**.nic.iveco.        **518400**    IN    AAAA    **2a01:8840:78:0:0:0:0:9**|
||c0.nic.iveco.        **518400**    IN    A    65.22.122.9|
#
## kerrylogistics
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## next
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--czr694b
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## rwe
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## voto
|expected|actual|
|--------|---|
|voto.            86400    IN    DS    **26875** **8** 2 **847371B1A0A21AE134A0E0C15B0E505BB4C88A26ED401DAFF4F4E8794C5B31A1**|voto.            86400    IN    DS    **8311** **7** **1 A538165168F076D2F400506D3A3FC7AE81E483A8**|
|a0.nic.voto.        **172800**    IN    A    65.22.168.1|**voto.            86400    IN    DS    8311 7 **2 **F689FF513836E44D785D8039338648D469B73D86D7000FB6D41624744A922DD6**|
|a0.nic.voto.        **172800**    IN    AAAA    2a01:8840:a2:0:0:0:0:1|a0.nic.voto.        **518400**    IN    A    65.22.168.1|
|a2.nic.voto.        **172800**    IN    **A**    **65.22.171.1**|a0.nic.voto.        **518400**    IN    AAAA    2a01:8840:a2:0:0:0:0:1|
|a2.nic.voto.        **172800**    IN    **AAAA**    **2a01:8840:a5:0:0:0:0:1**|a2.nic.voto.        **518400**    IN    **AAAA**    **2a01:8840:a5:0:0:0:0:1**|
|b0.nic.voto.        **172800**    IN    A    65.22.169.1|a2.nic.voto.        **518400**    IN    **A**    **65.22.171.1**|
|b0.nic.voto.        **172800**    IN    AAAA    2a01:8840:a3:0:0:0:0:1|b0.nic.voto.        **518400**    IN    A    65.22.169.1|
|c0.nic.voto.        **172800**    IN    A    65.22.170.1|b0.nic.voto.        **518400**    IN    AAAA    2a01:8840:a3:0:0:0:0:1|
|c0.nic.voto.        **172800**    IN    AAAA    2a01:8840:a4:0:0:0:0:1|c0.nic.voto.        **518400**    IN    A    65.22.170.1|
||c0.nic.voto.        **518400**    IN    AAAA    2a01:8840:a4:0:0:0:0:1|
#
## bbva
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ally
|expected|actual|
|--------|---|
|ally.            86400    IN    DS    **63106** **8** 2 **B7F4550D13DE48A5217E2DCCBD18FB872DB47C843028F48D413318271CC15261**|ally.            86400    IN    DS    **37575** **7** **1 EDFAB65412EF9EBFDCFD3E4BA386F9CCBE4BB624**|
|a0.nic.ally.        **172800**    IN    A    65.22.64.33|**ally.            86400    IN    DS    37575 7 **2 **2F79DA3A40F57A18E64FF9F50AA41725D7CA022EC065177C39908C79A421CDD8**|
|a0.nic.ally.        **172800**    IN    AAAA    2a01:8840:3e:0:0:0:0:33|a0.nic.ally.        **518400**    IN    A    65.22.64.33|
|a2.nic.ally.        **172800**    IN    **A**    **65.22.67.33**|a0.nic.ally.        **518400**    IN    AAAA    2a01:8840:3e:0:0:0:0:33|
|a2.nic.ally.        **172800**    IN    **AAAA**    **2a01:8840:41:0:0:0:0:33**|a2.nic.ally.        **518400**    IN    **AAAA**    **2a01:8840:41:0:0:0:0:33**|
|b0.nic.ally.        **172800**    IN    A    65.22.65.33|a2.nic.ally.        **518400**    IN    **A**    **65.22.67.33**|
|b0.nic.ally.        **172800**    IN    AAAA    2a01:8840:3f:0:0:0:0:33|b0.nic.ally.        **518400**    IN    A    65.22.65.33|
|c0.nic.ally.        **172800**    IN    **A**    **65.22.66.33**|b0.nic.ally.        **518400**    IN    AAAA    2a01:8840:3f:0:0:0:0:33|
|c0.nic.ally.        **172800**    IN    **AAAA**    **2a01:8840:40:0:0:0:0:33**|c0.nic.ally.        **518400**    IN    **AAAA**    **2a01:8840:40:0:0:0:0:33**|
||c0.nic.ally.        **518400**    IN    **A**    **65.22.66.33**|
#
## vote
|expected|actual|
|--------|---|
|vote.            86400    IN    DS    **62749** **8** 2 **101D2AE9C31FBE10078E74D477010AA5C8966D814421123A893B8B0E7B46891A**|vote.            86400    IN    DS    **17586** **7** **1 A0B4BE7608D8A2C883939B318B4AFCBC1959E9A0**|
|a0.nic.vote.        **172800**    IN    A    65.22.168.9|**vote.            86400    IN    DS    17586 7 **2 **8E80CDB7CB91AD73A41B39196A25DEF591BC1B51EAE1AE255181BCB8E2814F60**|
|a0.nic.vote.        **172800**    IN    AAAA    2a01:8840:a2:0:0:0:0:9|a0.nic.vote.        **518400**    IN    A    65.22.168.9|
|a2.nic.vote.        **172800**    IN    A    65.22.171.9|a0.nic.vote.        **518400**    IN    AAAA    2a01:8840:a2:0:0:0:0:9|
|**a2**.nic.vote.        **172800**    IN    AAAA    **2a01:8840:a5:0:0:0:0:9**|a2.nic.vote.        **518400**    IN    **AAAA    2a01:8840:a5:0:0:0:0:9**|
|b0.nic.vote.        **172800**    IN    A    65.22.169.9|**a2.nic.vote.        518400    IN    **A    65.22.171.9|
|**b0.nic.vote.        172800    IN    AAAA    2a01:8840:a3:0:0:0:0:9**|**b0**.nic.vote.        **518400**    IN    AAAA    **2a01:8840:a3:0:0:0:0:9**|
|c0.nic.vote.        **172800**    IN    A    65.22.170.9|b0.nic.vote.        **518400**    IN    A    65.22.169.9|
|c0.nic.vote.        **172800**    IN    AAAA    2a01:8840:a4:0:0:0:0:9|c0.nic.vote.        **518400**    IN    A    65.22.170.9|
||c0.nic.vote.        **518400**    IN    AAAA    2a01:8840:a4:0:0:0:0:9|
#
## llc
|expected|actual|
|--------|---|
|llc.            86400    IN    DS    **25591** **8** **2** **93C8B54BD9413A06DC25A32304B423342FD3273CA6785071C4BD18A2D8B04819**|llc.            86400    IN    DS    **50323** **7** **1** **195AC9A124A7C2E5E8EBF95E05F4669C6C569082**|
|**a0.nic.**llc.        **172800**    IN    **A**    **65.22.36.9**|llc.            **86400**    IN    **DS**    **50323** **7 2 8B39DC6547F248496DACB5ED2A038914BE941FE1E6BDE125ED07F27021FF1328**|
|a0.nic.llc.        **172800**    IN    AAAA    2a01:8840:26:0:0:0:0:9|a0.nic.llc.        **518400**    IN    AAAA    2a01:8840:26:0:0:0:0:9|
|**a2**.nic.llc.        **172800**    IN    A    65.22.**39**.9|**a0**.nic.llc.        **518400**    IN    A    65.22.**36**.9|
|a2.nic.llc.        **172800**    IN    AAAA    2a01:8840:29:0:0:0:0:9|a2.nic.llc.        **518400**    IN    AAAA    2a01:8840:29:0:0:0:0:9|
|**b0**.nic.llc.        **172800**    IN    A    65.22.**37**.9|**a2**.nic.llc.        **518400**    IN    A    65.22.**39**.9|
|b0.nic.llc.        **172800**    IN    AAAA    2a01:8840:27:0:0:0:0:9|b0.nic.llc.        **518400**    IN    AAAA    2a01:8840:27:0:0:0:0:9|
|c0.nic.llc.        **172800**    IN    A    65.22.38.9|**b0.nic.llc.        518400    IN    A    65.22.37.9**|
|c0.nic.llc.        **172800**    IN    AAAA    2a01:8840:28:0:0:0:0:9|c0.nic.llc.        **518400**    IN    A    65.22.38.9|
||c0.nic.llc.        **518400**    IN    AAAA    2a01:8840:28:0:0:0:0:9|
#
## green
|expected|actual|
|--------|---|
|green.            86400    IN    DS    **49042** **8** 2 **B0A053BC2903459BD6DC6060A822285C492FBB5F20346821A48C5EF3E6B0D29A**|green.            86400    IN    DS    **10671** **7** **1 5883309FABDAF8DFED06812D6B438553CD85FD1F**|
|a0.nic.green.        **172800**    IN    **A**    **65.22.32.9**|**green.            86400    IN    DS    10671 7 **2 **B713508BDF0A965472409EA6321967DB856C7CE7B99B9396ED25CDC406BCCA5A**|
|a0.nic.green.        **172800**    IN    **AAAA**    **2a01:8840:22:0:0:0:0:9**|a0.nic.green.        **518400**    IN    **AAAA**    **2a01:8840:22:0:0:0:0:9**|
|a2.nic.green.        **172800**    IN    A    65.22.35.9|a0.nic.green.        **518400**    IN    **A**    **65.22.32.9**|
|a2.nic.green.        **172800**    IN    AAAA    2a01:8840:25:0:0:0:0:9|a2.nic.green.        **518400**    IN    A    65.22.35.9|
|b0.nic.green.        **172800**    IN    A    65.22.33.9|a2.nic.green.        **518400**    IN    AAAA    2a01:8840:25:0:0:0:0:9|
|b0.nic.green.        **172800**    IN    AAAA    2a01:8840:23:0:0:0:0:9|b0.nic.green.        **518400**    IN    A    65.22.33.9|
|c0.nic.green.        **172800**    IN    A    65.22.34.9|b0.nic.green.        **518400**    IN    AAAA    2a01:8840:23:0:0:0:0:9|
|c0.nic.green.        **172800**    IN    AAAA    2a01:8840:24:0:0:0:0:9|c0.nic.green.        **518400**    IN    A    65.22.34.9|
||c0.nic.green.        **518400**    IN    AAAA    2a01:8840:24:0:0:0:0:9|
#
## xn--6frz82g
|expected|actual|
|--------|---|
|xn--6frz82g.        86400    IN    DS    **51310** **8** 2 **B725FA381426F5E3A9338C5C5A57447611ABA619E9675D9BF973D1D2A3B14B5E**|xn--6frz82g.        86400    IN    DS    **32256** **7** **1 FCE18B0EEE7F8DA4999A515CF554F4CFE6FBC8CE**|
|a0.nic.xn--6frz82g.    **172800**    IN    A    65.22.24.9|**xn--6frz82g.        86400    IN    DS    32256 7 **2 **AAA6B908BCDBFF82A49F4817A147A7E604A612616845FB3811E9B21B3BC6D2AF**|
|a0.nic.xn--6frz82g.    **172800**    IN    AAAA    2a01:8840:1a:0:0:0:0:9|a0.nic.xn--6frz82g.    **518400**    IN    A    65.22.24.9|
|a2.nic.xn--6frz82g.    **172800**    IN    A    65.22.27.9|a0.nic.xn--6frz82g.    **518400**    IN    AAAA    2a01:8840:1a:0:0:0:0:9|
|a2.nic.xn--6frz82g.    **172800**    IN    AAAA    2a01:8840:1d:0:0:0:0:9|a2.nic.xn--6frz82g.    **518400**    IN    A    65.22.27.9|
|b0.nic.xn--6frz82g.    **172800**    IN    A    65.22.25.9|a2.nic.xn--6frz82g.    **518400**    IN    AAAA    2a01:8840:1d:0:0:0:0:9|
|b0.nic.xn--6frz82g.    **172800**    IN    AAAA    2a01:8840:1b:0:0:0:0:9|b0.nic.xn--6frz82g.    **518400**    IN    A    65.22.25.9|
|c0.nic.xn--6frz82g.    **172800**    IN    **A**    **65.22.26.9**|b0.nic.xn--6frz82g.    **518400**    IN    AAAA    2a01:8840:1b:0:0:0:0:9|
|c0.nic.xn--6frz82g.    **172800**    IN    **AAAA**    **2a01:8840:1c:0:0:0:0:9**|c0.nic.xn--6frz82g.    **518400**    IN    **AAAA**    **2a01:8840:1c:0:0:0:0:9**|
||c0.nic.xn--6frz82g.    **518400**    IN    **A**    **65.22.26.9**|
#
## norton
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## windows
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## amfam
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## lifestyle
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## frontdoor
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--6qq986b3xl
|expected|actual|
|--------|---|
|**xn--6qq986b3xl.        86400    IN    DS    30406 8 2 A9B0F70F49B9E0819D93E5E98D1A24499ED86DC201C15D77EAF1ECBBF7C6D2AE**||
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|**xn--6qq986b3xl.        86400    IN    DS    30406 8 2 A9B0F70F49B9E0819D93E5E98D1A24499ED86DC201C15D77EAF1ECBBF7C6D2AE**|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
||j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## xn--j1aef
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--imr513n
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## abbvie
|expected|actual|
|--------|---|
|abbvie.            **86400**    IN    **DS**    **45109** **7 2 A1D723C297F1AB7E00B4D9F93064156EE15321F664397CBCD5217F6BFEECDE8F**|**a0.nic.**abbvie.        **518400**    IN    **AAAA**    **2a01:8840:9a:0:0:0:0:17**|
|a0.nic.abbvie.        **172800**    IN    A    65.22.156.17|a0.nic.abbvie.        **518400**    IN    A    65.22.156.17|
|**a0.nic.abbvie.        172800    IN    AAAA    2a01:8840:9a:0:0:0:0:17**|a2.nic.abbvie.        **518400**    IN    A    65.22.159.17|
|a2.nic.abbvie.        **172800**    IN    A    65.22.159.17|a2.nic.abbvie.        **518400**    IN    AAAA    2a01:8840:9d:0:0:0:0:17|
|a2.nic.abbvie.        **172800**    IN    AAAA    2a01:8840:9d:0:0:0:0:17|b0.nic.abbvie.        **518400**    IN    **AAAA**    **2a01:8840:9b:0:0:0:0:17**|
|b0.nic.abbvie.        **172800**    IN    **A**    **65.22.157.17**|b0.nic.abbvie.        **518400**    IN    **A**    **65.22.157.17**|
|b0.nic.abbvie.        **172800**    IN    **AAAA**    **2a01:8840:9b:0:0:0:0:17**|c0.nic.abbvie.        **518400**    IN    A    65.22.158.17|
|c0.nic.abbvie.        **172800**    IN    A    65.22.158.17|c0.nic.abbvie.        **518400**    IN    AAAA    2a01:8840:9c:0:0:0:0:17|
|c0.nic.abbvie.        **172800**    IN    AAAA    2a01:8840:9c:0:0:0:0:17||
#
## jio
|expected|actual|
|--------|---|
|jio.            86400    IN    DS    **5476** **8** **2** **D03F2390954D50F114B39620E940A7DE9D1FB60661CDEB43757B5D4A76FA8180**|jio.            86400    IN    DS    **61050** **7** **1** **A463C2DD74094E7FCFFCB08BF06E7CEC18AFACA7**|
|**a0.nic.**jio.        **172800**    IN    **A**    **65.22.212.33**|jio.            **86400**    IN    **DS**    **61050** **7 2 13655A34E30627124697A3AE76D595E16BFC502051EF5CD06F1A2FEBCC187EC8**|
|a0.nic.jio.        **172800**    IN    AAAA    2a01:8840:ce:0:0:0:0:33|a0.nic.jio.        **518400**    IN    AAAA    2a01:8840:ce:0:0:0:0:33|
|**a2**.nic.jio.        **172800**    IN    A    65.22.**215**.33|**a0**.nic.jio.        **518400**    IN    A    65.22.**212**.33|
|a2.nic.jio.        **172800**    IN    AAAA    2a01:8840:d1:0:0:0:0:33|a2.nic.jio.        **518400**    IN    AAAA    2a01:8840:d1:0:0:0:0:33|
|**b0**.nic.jio.        **172800**    IN    A    65.22.**213**.33|**a2**.nic.jio.        **518400**    IN    A    65.22.**215**.33|
|b0.nic.jio.        **172800**    IN    AAAA    2a01:8840:cf:0:0:0:0:33|b0.nic.jio.        **518400**    IN    AAAA    2a01:8840:cf:0:0:0:0:33|
|c0.nic.jio.        **172800**    IN    A    65.22.214.33|**b0.nic.jio.        518400    IN    A    65.22.213.33**|
|c0.nic.jio.        **172800**    IN    AAAA    2a01:8840:d0:0:0:0:0:33|c0.nic.jio.        **518400**    IN    A    65.22.214.33|
||c0.nic.jio.        **518400**    IN    AAAA    2a01:8840:d0:0:0:0:0:33|
#
## xn--30rr7y
|expected|actual|
|--------|---|
|**xn--30rr7y.        86400    IN    DS    42247 8 2 339254F4939C992790A50B1D257EA5C50BF4FC30F9D7B55A0FE875885AF8BB7A**||
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|**xn--30rr7y.        86400    IN    DS    42247 8 2 339254F4939C992790A50B1D257EA5C50BF4FC30F9D7B55A0FE875885AF8BB7A**|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
||j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## xn--efvy88h
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## nra
|expected|actual|
|--------|---|
|**nra.            86400    IN    DS    3700 7 2 0E97772CE2855079826C56AA83D787B8E42B323A2E8F3DF31555F49E91C516B9**||
|a0.nic.nra.        **172800**    IN    A    65.22.240.25|a0.nic.nra.        **518400**    IN    A    65.22.240.25|
|a0.nic.nra.        **172800**    IN    AAAA    2a01:8840:ea:0:0:0:0:25|a0.nic.nra.        **518400**    IN    AAAA    2a01:8840:ea:0:0:0:0:25|
|a2.nic.nra.        **172800**    IN    **A**    **65.22.243.25**|a2.nic.nra.        **518400**    IN    **AAAA**    **2a01:8840:ed:0:0:0:0:25**|
|a2.nic.nra.        **172800**    IN    **AAAA**    **2a01:8840:ed:0:0:0:0:25**|a2.nic.nra.        **518400**    IN    **A**    **65.22.243.25**|
|b0.nic.nra.        **172800**    IN    A    65.22.241.25|b0.nic.nra.        **518400**    IN    A    65.22.241.25|
|b0.nic.nra.        **172800**    IN    AAAA    2a01:8840:eb:0:0:0:0:25|b0.nic.nra.        **518400**    IN    AAAA    2a01:8840:eb:0:0:0:0:25|
|c0.nic.nra.        **172800**    IN    A    65.22.242.25|c0.nic.nra.        **518400**    IN    A    65.22.242.25|
|c0.nic.nra.        **172800**    IN    AAAA    2a01:8840:ec:0:0:0:0:25|c0.nic.nra.        **518400**    IN    AAAA    2a01:8840:ec:0:0:0:0:25|
#
## aquarelle
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## nokia
|expected|actual|
|--------|---|
|nokia.            86400    IN    DS    **38794** **8** 2 **5D3C0F0B92084EB734E6E06364681B3BB051087A15EBE6F468B2974C5F197AB1**|nokia.            86400    IN    DS    **29661** **7** **1 8FF2E988BF04AD610E68536645F11267972C28B3**|
|a0.nic.nokia.        **172800**    IN    A    65.22.148.17|**nokia.            86400    IN    DS    29661 7 **2 **C6A6724F8E4E6361C7349BF9703F95EE1261060E60CE8C6FEE468F9D41D79D59**|
|a0.nic.nokia.        **172800**    IN    AAAA    2a01:8840:92:0:0:0:0:17|a0.nic.nokia.        **518400**    IN    A    65.22.148.17|
|a2.nic.nokia.        **172800**    IN    A    65.22.151.17|a0.nic.nokia.        **518400**    IN    AAAA    2a01:8840:92:0:0:0:0:17|
|**a2**.nic.nokia.        **172800**    IN    AAAA    **2a01:8840:95:0:0:0:0:17**|a2.nic.nokia.        **518400**    IN    **AAAA    2a01:8840:95:0:0:0:0:17**|
|b0.nic.nokia.        **172800**    IN    A    65.22.149.17|**a2.nic.nokia.        518400    IN    **A    65.22.151.17|
|**b0**.nic.nokia.        **172800**    IN    AAAA    **2a01:8840:93:0:0:0:0:17**|**b0**.nic.nokia.        **518400**    IN    AAAA    **2a01:8840:93:0:0:0:0:17**|
|c0.nic.nokia.        **172800**    IN    A    65.22.150.17|b0.nic.nokia.        **518400**    IN    A    65.22.149.17|
|**c0.nic.nokia.        172800    IN    AAAA    2a01:8840:94:0:0:0:0:17**|**c0**.nic.nokia.        **518400**    IN    AAAA    **2a01:8840:94:0:0:0:0:17**|
||c0.nic.nokia.        **518400**    IN    A    65.22.150.17|
#
## omega
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## cars
|expected|actual|
|--------|---|
|**cars.            172800    IN    NS    a.nic.cars.**||
|**cars.            172800    IN    NS    b.nic.cars.**||
|**cars.            172800    IN    NS    c.nic.cars.**||
|**cars.            172800    IN    NS    d.nic.cars.**||
|cars.            86400    IN    DS    **26272** 5 1 **2FFCC79B8797324D59B76C73B30B390DE6E17A08**|cars.            86400    IN    DS    **33842** 5 1 **2EC42D8F246D7B2690E6ABD65C56E3D6C3A863A1**|
|cars.            86400    IN    DS    **26272** 5 2 **8253077194F36991396AC49542ED2BE77D88E972D5ABDB0D832F2D5CD2C7F71A**|cars.            86400    IN    DS    **33842** 5 2 **2CD1CFB06C838FECE514D8008EF5F3FC1D34E7DF15D2E736107483C6779B7E7F**|
|**cars.            86400    IN    DS    56833 5 2 5AD7A5C1FA890745F1746767C20FDC1E2D6F1CBB5E461A40DE94576BED7682FA**||
||**cars.            86400    IN    DS    56833 5 2 5AD7A5C1FA890745F1746767C20FDC1E2D6F1CBB5E461A40DE94576BED7682FA**|
|**a**.**nic**.**cars**.        **172800**    IN    A    **194.169.218.129**|**ns2**.**uniregistry**.**info**.    **518400**    IN    A    64.**96**.**2**.**1**|
|**a.nic.cars.        172800    IN    AAAA    2001:67c:13cc:0:0:0:1:129**|**ns4**.uniregistry.info.    **518400**    IN    **AAAA**    **2620:10a:80ab:0:0:0:0:3**|
|**b.nic.cars.        172800    IN    A    185.24.**64.**129**|ns4.uniregistry.info.    **518400**    IN    A    185.159.198.3|
|**b**.**nic**.**cars.**        **172800    IN    AAAA    2a04:2b00:13cc:0:0:0:1:129**|**ns1**.uniregistry.**net**.    **518400**    IN    AAAA    **2620:57:4000:1:0:0:0:1**|
|**c**.**nic.cars.        172800    IN    A    212.18.248.129**|ns1.uniregistry.net.    **518400**    IN    A    64.96.1.1|
|**c.nic.cars.        172800    IN    AAAA    2a04:2b00:13ee:0:0:0:0:129**|ns3.uniregistry.net.    **518400**    IN    A    185.159.197.3|
|**d.nic.cars.        172800    IN    A    212.18.249.129**|ns3.uniregistry.net.    **518400**    IN    AAAA    2620:10a:80aa:0:0:0:0:3|
|**d.nic.cars.        172800    IN    AAAA    2a04:2b00:13ff:0:0:0:0:129**||
|**ns2.**uniregistry.info.    **172800**    IN    **A**    **64.96.2.1**||
|ns4.uniregistry.info.    **172800**    IN    A    185.159.198.3||
|**ns4**.uniregistry.**info**.    **172800**    IN    AAAA    **2620:10a:80ab:0:0:0:0:3**||
|ns1.uniregistry.net.    **172800**    IN    A    64.96.1.1||
|**ns1.uniregistry.net.    172800    IN    AAAA    2620:57:4000:1:0:0:0:1**||
|ns3.uniregistry.net.    **172800**    IN    A    185.159.197.3||
|ns3.uniregistry.net.    **172800**    IN    AAAA    2620:10a:80aa:0:0:0:0:3||
#
## phone
|expected|actual|
|--------|---|
|phone.            86400    IN    DS    **18829** **8** **2** **B7809834406510FCBEA1AAFA42F0BD2E7F4096BEE97D8B7FD5964CDB39C607B4**|phone.            86400    IN    DS    **39136** **7** **1** **CDD1D5514CC834FEA33FE328FF3ADC5B48047892**|
|**a0.nic.**phone.        **172800**    IN    **A**    **65.22.96.17**|phone.            **86400**    IN    **DS**    **39136** **7 2 628A9B396BADF11D234C74C29881403AF3238CE9D8C6F6D4DB29756D56268E47**|
|a0.nic.phone.        **172800**    IN    AAAA    2a01:8840:5e:0:0:0:0:17|a0.nic.phone.        **518400**    IN    AAAA    2a01:8840:5e:0:0:0:0:17|
|**a2**.nic.phone.        **172800**    IN    A    65.22.**99**.17|**a0**.nic.phone.        **518400**    IN    A    65.22.**96**.17|
|a2.nic.phone.        **172800**    IN    AAAA    2a01:8840:61:0:0:0:0:17|a2.nic.phone.        **518400**    IN    AAAA    2a01:8840:61:0:0:0:0:17|
|**b0**.nic.phone.        **172800**    IN    A    65.22.**97**.17|**a2**.nic.phone.        **518400**    IN    A    65.22.**99**.17|
|b0.nic.phone.        **172800**    IN    AAAA    2a01:8840:5f:0:0:0:0:17|b0.nic.phone.        **518400**    IN    AAAA    2a01:8840:5f:0:0:0:0:17|
|c0.nic.phone.        **172800**    IN    A    65.22.98.17|**b0.nic.phone.        518400    IN    A    65.22.97.17**|
|c0.nic.phone.        **172800**    IN    AAAA    2a01:8840:60:0:0:0:0:17|c0.nic.phone.        **518400**    IN    A    65.22.98.17|
||c0.nic.phone.        **518400**    IN    AAAA    2a01:8840:60:0:0:0:0:17|
#
## pwc
|expected|actual|
|--------|---|
|pwc.            86400    IN    DS    **50191** **8** **2** **53A702C1BC2E7246D8027839BC8C43ECB48A28139D2ECBC0350E4C6CA3BC623A**|pwc.            86400    IN    DS    **46395** **7** **1** **0370D2A8FFC791ACB8728C6A384A9FD1667BAE38**|
|**a0.nic.**pwc.        **172800**    IN    **A**    **65.22.80.9**|pwc.            **86400**    IN    **DS**    **46395** **7 2 F12AC63CDB08F8C0B9312F41C41A6E791045A16B8435011EC6411AF191A21335**|
|a0.nic.pwc.        **172800**    IN    AAAA    2a01:8840:4e:0:0:0:0:9|a0.nic.pwc.        **518400**    IN    AAAA    2a01:8840:4e:0:0:0:0:9|
|**a2**.nic.pwc.        **172800**    IN    A    65.22.**83**.9|**a0**.nic.pwc.        **518400**    IN    A    65.22.**80**.9|
|a2.nic.pwc.        **172800**    IN    AAAA    2a01:8840:51:0:0:0:0:9|a2.nic.pwc.        **518400**    IN    AAAA    2a01:8840:51:0:0:0:0:9|
|b0.nic.pwc.        **172800**    IN    A    65.22.81.9|**a2.nic.pwc.        518400    IN    A    65.22.83.9**|
|b0.nic.pwc.        **172800**    IN    AAAA    2a01:8840:4f:0:0:0:0:9|b0.nic.pwc.        **518400**    IN    A    65.22.81.9|
|c0.nic.pwc.        **172800**    IN    **A**    **65.22.82.9**|b0.nic.pwc.        **518400**    IN    AAAA    2a01:8840:4f:0:0:0:0:9|
|c0.nic.pwc.        **172800**    IN    **AAAA**    **2a01:8840:50:0:0:0:0:9**|c0.nic.pwc.        **518400**    IN    **AAAA**    **2a01:8840:50:0:0:0:0:9**|
||c0.nic.pwc.        **518400**    IN    **A**    **65.22.82.9**|
#
## stockholm
|expected|actual|
|--------|---|
|**stockholm.        86400    IN    DS    1816 7 2 9B9D7A1B744A60DDA7E6B8C1F1D8D72142A524AB6CDB7429B3183666615AB45E**||
|a0.nic.stockholm.    **172800**    IN    **A**    **65.22.220.41**|a0.nic.stockholm.    **518400**    IN    **AAAA**    **2a01:8840:d6:0:0:0:0:41**|
|a0.nic.stockholm.    **172800**    IN    **AAAA**    **2a01:8840:d6:0:0:0:0:41**|a0.nic.stockholm.    **518400**    IN    **A**    **65.22.220.41**|
|a2.nic.stockholm.    **172800**    IN    A    65.22.223.41|a2.nic.stockholm.    **518400**    IN    A    65.22.223.41|
|a2.nic.stockholm.    **172800**    IN    AAAA    2a01:8840:d9:0:0:0:0:41|a2.nic.stockholm.    **518400**    IN    AAAA    2a01:8840:d9:0:0:0:0:41|
|b0.nic.stockholm.    **172800**    IN    A    65.22.221.41|b0.nic.stockholm.    **518400**    IN    A    65.22.221.41|
|b0.nic.stockholm.    **172800**    IN    AAAA    2a01:8840:d7:0:0:0:0:41|b0.nic.stockholm.    **518400**    IN    AAAA    2a01:8840:d7:0:0:0:0:41|
|c0.nic.stockholm.    **172800**    IN    A    65.22.222.41|c0.nic.stockholm.    **518400**    IN    A    65.22.222.41|
|c0.nic.stockholm.    **172800**    IN    AAAA    2a01:8840:d8:0:0:0:0:41|c0.nic.stockholm.    **518400**    IN    AAAA    2a01:8840:d8:0:0:0:0:41|
#
## xn--3oq18vl8pn36a
|expected|actual|
|--------|---|
|xn--3oq18vl8pn36a.    86400    IN    DS    **59236** **8** 2 **BC29589725F48472D4D1F8B70CCF885CB674F13ACDB34FAADDF9CD6C01D9FF29**|xn--3oq18vl8pn36a.    86400    IN    DS    **62449** **7** **1 07FA270D7B8F681DA0505A8F1D286889BBE85914**|
|a0.nic.xn--3oq18vl8pn36a.    **172800**    IN    A    65.22.208.1|**xn--3oq18vl8pn36a.    86400    IN    DS    62449 7 **2 **285188DAE1DD0AF87A6EBC272FF7690FE94C9256ED4EE9B1ADEA8A0714DFF3A4**|
|a0.nic.xn--3oq18vl8pn36a.    **172800**    IN    AAAA    2a01:8840:ca:0:0:0:0:1|a0.nic.xn--3oq18vl8pn36a.    **518400**    IN    A    65.22.208.1|
|a2.nic.xn--3oq18vl8pn36a.    **172800**    IN    A    65.22.211.1|a0.nic.xn--3oq18vl8pn36a.    **518400**    IN    AAAA    2a01:8840:ca:0:0:0:0:1|
|a2.nic.xn--3oq18vl8pn36a.    **172800**    IN    AAAA    2a01:8840:cd:0:0:0:0:1|a2.nic.xn--3oq18vl8pn36a.    **518400**    IN    A    65.22.211.1|
|b0.nic.xn--3oq18vl8pn36a.    **172800**    IN    A    65.22.209.1|a2.nic.xn--3oq18vl8pn36a.    **518400**    IN    AAAA    2a01:8840:cd:0:0:0:0:1|
|b0.nic.xn--3oq18vl8pn36a.    **172800**    IN    AAAA    2a01:8840:cb:0:0:0:0:1|b0.nic.xn--3oq18vl8pn36a.    **518400**    IN    A    65.22.209.1|
|c0.nic.xn--3oq18vl8pn36a.    **172800**    IN    **A**    **65.22.210.1**|b0.nic.xn--3oq18vl8pn36a.    **518400**    IN    AAAA    2a01:8840:cb:0:0:0:0:1|
|c0.nic.xn--3oq18vl8pn36a.    **172800**    IN    **AAAA**    **2a01:8840:cc:0:0:0:0:1**|c0.nic.xn--3oq18vl8pn36a.    **518400**    IN    **AAAA**    **2a01:8840:cc:0:0:0:0:1**|
||c0.nic.xn--3oq18vl8pn36a.    **518400**    IN    **A**    **65.22.210.1**|
#
## cityeats
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## yachts
|expected|actual|
|--------|---|
|**yachts.            86400    IN    DS    65265 7 2 ED9E6FE2D28FA9DEB3E6A11C60E1465EA72A26919467AA9F84AB1BB73C347D11**|a0.nic.yachts.        **518400**    IN    A    65.22.100.1|
|a0.nic.yachts.        **172800**    IN    A    65.22.100.1|a0.nic.yachts.        **518400**    IN    AAAA    2a01:8840:62:0:0:0:0:1|
|a0.nic.yachts.        **172800**    IN    AAAA    2a01:8840:62:0:0:0:0:1|a2.nic.yachts.        **518400**    IN    A    65.22.103.1|
|a2.nic.yachts.        **172800**    IN    A    65.22.103.1|a2.nic.yachts.        **518400**    IN    AAAA    2a01:8840:65:0:0:0:0:1|
|a2.nic.yachts.        **172800**    IN    AAAA    2a01:8840:65:0:0:0:0:1|b0.nic.yachts.        **518400**    IN    **AAAA    2a01:8840:63:0:0:0:0:1**|
|b0.nic.yachts.        **172800**    IN    A    65.22.101.1|**b0.nic.yachts.        518400    IN    **A    65.22.101.1|
|**b0**.nic.yachts.        **172800**    IN    AAAA    **2a01:8840:63:0:0:0:0:1**|**c0**.nic.yachts.        **518400**    IN    AAAA    **2a01:8840:64:0:0:0:0:1**|
|c0.nic.yachts.        **172800**    IN    A    65.22.102.1|c0.nic.yachts.        **518400**    IN    A    65.22.102.1|
|**c0.nic.yachts.        172800    IN    AAAA    2a01:8840:64:0:0:0:0:1**||
#
## corsica
|expected|actual|
|--------|---|
|corsica.        86400    IN    DS    **18960** **13** 2 **89841E201926A237E22A8442C6E557DCF3C60F973D0FFB2B40D4AE07931F080D**|corsica.        86400    IN    DS    **63082** **8** 2 **84C01935DA9B0DC9B26FEE9D2C390F5FC2BD946CD5C0B325327BF83914349AE2**|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## extraspace
|expected|actual|
|--------|---|
|**extraspace.        86400    IN    DS    32563 7 2 DF1DE65A0A08F3B3108985AC8DCB51F20188421989A1021237524299931A1198**||
|a0.nic.extraspace.    **172800**    IN    A    65.22.116.1|a0.nic.extraspace.    **518400**    IN    A    65.22.116.1|
|a0.nic.extraspace.    **172800**    IN    AAAA    2a01:8840:72:0:0:0:0:1|a0.nic.extraspace.    **518400**    IN    AAAA    2a01:8840:72:0:0:0:0:1|
|a2.nic.extraspace.    **172800**    IN    **A**    **65.22.119.1**|a2.nic.extraspace.    **518400**    IN    **AAAA**    **2a01:8840:75:0:0:0:0:1**|
|a2.nic.extraspace.    **172800**    IN    **AAAA**    **2a01:8840:75:0:0:0:0:1**|a2.nic.extraspace.    **518400**    IN    **A**    **65.22.119.1**|
|b0.nic.extraspace.    **172800**    IN    A    65.22.117.1|b0.nic.extraspace.    **518400**    IN    A    65.22.117.1|
|b0.nic.extraspace.    **172800**    IN    AAAA    2a01:8840:73:0:0:0:0:1|b0.nic.extraspace.    **518400**    IN    AAAA    2a01:8840:73:0:0:0:0:1|
|c0.nic.extraspace.    **172800**    IN    A    65.22.118.1|c0.nic.extraspace.    **518400**    IN    A    65.22.118.1|
|c0.nic.extraspace.    **172800**    IN    AAAA    2a01:8840:74:0:0:0:0:1|c0.nic.extraspace.    **518400**    IN    AAAA    2a01:8840:74:0:0:0:0:1|
#
## xn--jlq61u9w7b
|expected|actual|
|--------|---|
|xn--jlq61u9w7b.        86400    IN    DS    **1039** **8** 2 **BF62B17707761B613C23BDBBDB00C0A3127AE7497FF1C62E17177B44222CBA26**|xn--jlq61u9w7b.        86400    IN    DS    **41248** **7** **1 41DFB5CFC83D153291D2B6CF700CF8A002381BB8**|
|a0.nic.xn--jlq61u9w7b.    **172800**    IN    **A**    **65.22.244.1**|**xn--jlq61u9w7b.        86400    IN    DS    41248 7 **2 **0EC20DA00BC41AB2FD073614E98DFE93A25E21873A9BEAEA53C0BAF998BB6B60**|
|a0.nic.xn--jlq61u9w7b.    **172800**    IN    **AAAA**    **2a01:8840:ee:0:0:0:0:1**|a0.nic.xn--jlq61u9w7b.    **518400**    IN    **AAAA**    **2a01:8840:ee:0:0:0:0:1**|
|a2.nic.xn--jlq61u9w7b.    **172800**    IN    A    65.22.247.1|a0.nic.xn--jlq61u9w7b.    **518400**    IN    **A**    **65.22.244.1**|
|a2.nic.xn--jlq61u9w7b.    **172800**    IN    AAAA    2a01:8840:f1:0:0:0:0:1|a2.nic.xn--jlq61u9w7b.    **518400**    IN    A    65.22.247.1|
|b0.nic.xn--jlq61u9w7b.    **172800**    IN    **A**    **65.22.245.1**|a2.nic.xn--jlq61u9w7b.    **518400**    IN    AAAA    2a01:8840:f1:0:0:0:0:1|
|b0.nic.xn--jlq61u9w7b.    **172800**    IN    **AAAA**    **2a01:8840:ef:0:0:0:0:1**|b0.nic.xn--jlq61u9w7b.    **518400**    IN    **AAAA**    **2a01:8840:ef:0:0:0:0:1**|
|c0.nic.xn--jlq61u9w7b.    **172800**    IN    A    65.22.246.1|b0.nic.xn--jlq61u9w7b.    **518400**    IN    **A**    **65.22.245.1**|
|c0.nic.xn--jlq61u9w7b.    **172800**    IN    AAAA    2a01:8840:f0:0:0:0:0:1|c0.nic.xn--jlq61u9w7b.    **518400**    IN    A    65.22.246.1|
||c0.nic.xn--jlq61u9w7b.    **518400**    IN    AAAA    2a01:8840:f0:0:0:0:0:1|
#
## nissay
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## reliance
|expected|actual|
|--------|---|
|reliance.        86400    IN    DS    **19927** **8** 2 **DB9D2DCF05506FCB1F593CE8F9B5A0155E68706CB9BDFE7A945074312BC8F896**|reliance.        86400    IN    DS    **54214** **7** **1 D7B1272496615834548FD39B38AD9104718F288E**|
|a0.nic.reliance.    **172800**    IN    A    65.22.108.25|**reliance.        86400    IN    DS    54214 7 **2 **72F9F4415EBE13628D09DFCD5FDC5C079B07EC5186CB89F28541C7A5C42A457E**|
|a0.nic.reliance.    **172800**    IN    AAAA    2a01:8840:6a:0:0:0:0:25|a0.nic.reliance.    **518400**    IN    A    65.22.108.25|
|a2.nic.reliance.    **172800**    IN    **A**    **65.22.111.25**|a0.nic.reliance.    **518400**    IN    AAAA    2a01:8840:6a:0:0:0:0:25|
|a2.nic.reliance.    **172800**    IN    **AAAA**    **2a01:8840:6d:0:0:0:0:25**|a2.nic.reliance.    **518400**    IN    **AAAA**    **2a01:8840:6d:0:0:0:0:25**|
|b0.nic.reliance.    **172800**    IN    A    65.22.109.25|a2.nic.reliance.    **518400**    IN    **A**    **65.22.111.25**|
|b0.nic.reliance.    **172800**    IN    AAAA    2a01:8840:6b:0:0:0:0:25|b0.nic.reliance.    **518400**    IN    A    65.22.109.25|
|c0.nic.reliance.    **172800**    IN    **A**    **65.22.110.25**|b0.nic.reliance.    **518400**    IN    AAAA    2a01:8840:6b:0:0:0:0:25|
|c0.nic.reliance.    **172800**    IN    **AAAA**    **2a01:8840:6c:0:0:0:0:25**|c0.nic.reliance.    **518400**    IN    **AAAA**    **2a01:8840:6c:0:0:0:0:25**|
||c0.nic.reliance.    **518400**    IN    **A**    **65.22.110.25**|
#
## vegas
|expected|actual|
|--------|---|
|**vegas.            86400    IN    DS    55438 7 2 164EE0F2CBFA43345D7ED9DBA4A48B7E97B523D8FBAC5627B8D2A77B45DAE5E6**|a0.nic.vegas.        **518400**    IN    A    65.22.68.17|
|a0.nic.vegas.        **172800**    IN    A    65.22.68.17|a0.nic.vegas.        **518400**    IN    AAAA    2a01:8840:42:0:0:0:0:17|
|a0.nic.vegas.        **172800**    IN    AAAA    2a01:8840:42:0:0:0:0:17|a2.nic.vegas.        **518400**    IN    **AAAA**    **2a01:8840:45:0:0:0:0:17**|
|a2.nic.vegas.        **172800**    IN    **A**    **65.22.71.17**|a2.nic.vegas.        **518400**    IN    **A**    **65.22.71.17**|
|a2.nic.vegas.        **172800**    IN    **AAAA**    **2a01:8840:45:0:0:0:0:17**|b0.nic.vegas.        **518400**    IN    A    65.22.69.17|
|b0.nic.vegas.        **172800**    IN    A    65.22.69.17|b0.nic.vegas.        **518400**    IN    AAAA    2a01:8840:43:0:0:0:0:17|
|b0.nic.vegas.        **172800**    IN    AAAA    2a01:8840:43:0:0:0:0:17|c0.nic.vegas.        **518400**    IN    A    65.22.70.17|
|c0.nic.vegas.        **172800**    IN    A    65.22.70.17|c0.nic.vegas.        **518400**    IN    AAAA    2a01:8840:44:0:0:0:0:17|
|c0.nic.vegas.        **172800**    IN    AAAA    2a01:8840:44:0:0:0:0:17||
#
## jll
|expected|actual|
|--------|---|
|jll.            86400    IN    DS    **34711** **8** 2 **2684574B7AC4339237FA607C55C1244D45C6C7C86B143C9240A72C2F62A012E4**|jll.            86400    IN    DS    **38338** **7** **1 F241CBADD91087534E1D2058CEC3DDA2AA2D3874**|
|a0.nic.jll.        **172800**    IN    **A**    **65.22.148.9**|**jll.            86400    IN    DS    38338 7 **2 **B4CA4D71547974836BDE20A9E83E11EC00DA48046E337B6D0FD0B0C73F95D86C**|
|a0.nic.jll.        **172800**    IN    **AAAA**    **2a01:8840:92:0:0:0:0:9**|a0.nic.jll.        **518400**    IN    **AAAA**    **2a01:8840:92:0:0:0:0:9**|
|a2.nic.jll.        **172800**    IN    A    65.22.151.9|a0.nic.jll.        **518400**    IN    **A**    **65.22.148.9**|
|a2.nic.jll.        **172800**    IN    AAAA    2a01:8840:95:0:0:0:0:9|a2.nic.jll.        **518400**    IN    A    65.22.151.9|
|b0.nic.jll.        **172800**    IN    A    65.22.149.9|a2.nic.jll.        **518400**    IN    AAAA    2a01:8840:95:0:0:0:0:9|
|b0.nic.jll.        **172800**    IN    AAAA    2a01:8840:93:0:0:0:0:9|b0.nic.jll.        **518400**    IN    A    65.22.149.9|
|c0.nic.jll.        **172800**    IN    A    65.22.150.9|b0.nic.jll.        **518400**    IN    AAAA    2a01:8840:93:0:0:0:0:9|
|c0.nic.jll.        **172800**    IN    AAAA    2a01:8840:94:0:0:0:0:9|c0.nic.jll.        **518400**    IN    A    65.22.150.9|
||c0.nic.jll.        **518400**    IN    AAAA    2a01:8840:94:0:0:0:0:9|
#
## airbus
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## unicom
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## ubs
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## baidu
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## rogers
|expected|actual|
|--------|---|
|rogers.            86400    IN    DS    **46654** **8** **2** **36DCB391639DBEF1612BFFC2103E2CE37D3167BBA29AA713FAE7CEB540F6EB71**|rogers.            86400    IN    DS    **59283** **7** **1** **A302BFE8A8310053E31CBAEA9822AC9C89CD02FD**|
|**a0.nic.**rogers.        **172800**    IN    **A**    **65.22.108.33**|rogers.            **86400**    IN    **DS**    **59283** **7 2 A799A2143184A61D7BF63A4C20F4CEBF1DCF40B6D501837131E0CD3F5EBD5EE3**|
|a0.nic.rogers.        **172800**    IN    AAAA    2a01:8840:6a:0:0:0:0:33|a0.nic.rogers.        **518400**    IN    AAAA    2a01:8840:6a:0:0:0:0:33|
|**a2**.nic.rogers.        **172800**    IN    A    65.22.**111**.33|**a0**.nic.rogers.        **518400**    IN    A    65.22.**108**.33|
|a2.nic.rogers.        **172800**    IN    AAAA    2a01:8840:6d:0:0:0:0:33|a2.nic.rogers.        **518400**    IN    AAAA    2a01:8840:6d:0:0:0:0:33|
|**b0**.nic.rogers.        **172800**    IN    A    65.22.**109**.33|**a2**.nic.rogers.        **518400**    IN    A    65.22.**111**.33|
|b0.nic.rogers.        **172800**    IN    AAAA    2a01:8840:6b:0:0:0:0:33|b0.nic.rogers.        **518400**    IN    AAAA    2a01:8840:6b:0:0:0:0:33|
|**c0**.nic.rogers.        **172800**    IN    A    65.22.**110**.33|**b0**.nic.rogers.        **518400**    IN    A    65.22.**109**.33|
|c0.nic.rogers.        **172800**    IN    AAAA    2a01:8840:6c:0:0:0:0:33|c0.nic.rogers.        **518400**    IN    AAAA    2a01:8840:6c:0:0:0:0:33|
||**c0.nic.rogers.        518400    IN    A    65.22.110.33**|
#
## xn--42c2d9a
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## fairwinds
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## audi
|expected|actual|
|--------|---|
|**audi.            86400    IN    DS    9021 7 2 A3BBC94CBEEDF9531FBBC8CF33162E53B9331385A6A7381DF395FC2FAAC8E75C**||
|a0.nic.audi.        **172800**    IN    A    65.22.208.17|a0.nic.audi.        **518400**    IN    A    65.22.208.17|
|a0.nic.audi.        **172800**    IN    AAAA    2a01:8840:ca:0:0:0:0:17|a0.nic.audi.        **518400**    IN    AAAA    2a01:8840:ca:0:0:0:0:17|
|a2.nic.audi.        **172800**    IN    A    65.22.211.17|a2.nic.audi.        **518400**    IN    A    65.22.211.17|
|a2.nic.audi.        **172800**    IN    AAAA    2a01:8840:cd:0:0:0:0:17|a2.nic.audi.        **518400**    IN    AAAA    2a01:8840:cd:0:0:0:0:17|
|b0.nic.audi.        **172800**    IN    A    65.22.209.17|b0.nic.audi.        **518400**    IN    A    65.22.209.17|
|b0.nic.audi.        **172800**    IN    AAAA    2a01:8840:cb:0:0:0:0:17|b0.nic.audi.        **518400**    IN    AAAA    2a01:8840:cb:0:0:0:0:17|
|c0.nic.audi.        **172800**    IN    A    65.22.210.17|c0.nic.audi.        **518400**    IN    A    65.22.210.17|
|c0.nic.audi.        **172800**    IN    AAAA    2a01:8840:cc:0:0:0:0:17|c0.nic.audi.        **518400**    IN    AAAA    2a01:8840:cc:0:0:0:0:17|
#
## cruise
|expected|actual|
|--------|---|
|cruise.            86400    IN    DS    **33220** **8** 2 **254D748F9E700BD632010EEFFE96CC5A1DFEF5B4A85A18A1AB4962EA81F9937F**|cruise.            86400    IN    DS    **62550** **7** **1 6BE1FA931719330E44C14F8BCDB0AEC8C1765718**|
|a0.nic.cruise.        **172800**    IN    **A**    **65.22.192.25**|**cruise.            86400    IN    DS    62550 7 **2 **F4A23D33454784D337840885289DFA81CB23A2F65009DECF86C2C84C03DE91F2**|
|a0.nic.cruise.        **172800**    IN    **AAAA**    **2a01:8840:ba:0:0:0:0:25**|a0.nic.cruise.        **518400**    IN    **AAAA**    **2a01:8840:ba:0:0:0:0:25**|
|a2.nic.cruise.        **172800**    IN    AAAA    2a01:8840:bd:0:0:0:0:25|a0.nic.cruise.        **518400**    IN    **A**    **65.22.192.25**|
|a2.nic.cruise.        **172800**    IN    A    65.22.195.25|a2.nic.cruise.        **518400**    IN    AAAA    2a01:8840:bd:0:0:0:0:25|
|b0.nic.cruise.        **172800**    IN    A    65.22.193.25|a2.nic.cruise.        **518400**    IN    A    65.22.195.25|
|b0.nic.cruise.        **172800**    IN    AAAA    2a01:8840:bb:0:0:0:0:25|b0.nic.cruise.        **518400**    IN    A    65.22.193.25|
|c0.nic.cruise.        **172800**    IN    A    65.22.194.25|b0.nic.cruise.        **518400**    IN    AAAA    2a01:8840:bb:0:0:0:0:25|
|c0.nic.cruise.        **172800**    IN    AAAA    2a01:8840:bc:0:0:0:0:25|c0.nic.cruise.        **518400**    IN    A    65.22.194.25|
||c0.nic.cruise.        **518400**    IN    AAAA    2a01:8840:bc:0:0:0:0:25|
#
## xn--8y0a063a
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## raid
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--fiq64b
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## hughes
|expected|actual|
|--------|---|
|hughes.            86400    IN    DS    **64252** **8** **2** **29A6AE50D287B301E6624077720BEA37AA9CD752183DD014E7F3028CBCB740F2**|hughes.            86400    IN    DS    **4783** **7** **1** **8DB106545645B7F77E2A82C23A18AA8BF1A62146**|
|**a0.nic.**hughes.        **172800**    IN    **A**    **65.22.108.1**|hughes.            **86400**    IN    **DS**    **4783** **7 2 73FD0A64DC60ABEB6DDAE94E835686C9759BF2E9D6AA11BD0AA70B67831C3A1E**|
|a0.nic.hughes.        **172800**    IN    AAAA    2a01:8840:6a:0:0:0:0:1|a0.nic.hughes.        **518400**    IN    AAAA    2a01:8840:6a:0:0:0:0:1|
|**a2**.nic.hughes.        **172800**    IN    A    65.22.**111**.1|**a0**.nic.hughes.        **518400**    IN    A    65.22.**108**.1|
|a2.nic.hughes.        **172800**    IN    AAAA    2a01:8840:6d:0:0:0:0:1|a2.nic.hughes.        **518400**    IN    AAAA    2a01:8840:6d:0:0:0:0:1|
|b0.nic.hughes.        **172800**    IN    A    65.22.109.1|**a2.nic.hughes.        518400    IN    A    65.22.111.1**|
|b0.nic.hughes.        **172800**    IN    AAAA    2a01:8840:6b:0:0:0:0:1|b0.nic.hughes.        **518400**    IN    A    65.22.109.1|
|c0.nic.hughes.        **172800**    IN    **A**    **65.22.110.1**|b0.nic.hughes.        **518400**    IN    AAAA    2a01:8840:6b:0:0:0:0:1|
|c0.nic.hughes.        **172800**    IN    **AAAA**    **2a01:8840:6c:0:0:0:0:1**|c0.nic.hughes.        **518400**    IN    **AAAA**    **2a01:8840:6c:0:0:0:0:1**|
||c0.nic.hughes.        **518400**    IN    **A**    **65.22.110.1**|
#
## pars
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|ns.cocca.fr.        **518400**    IN    **A**    **185**.**17.236.123**|
|**a**.ns.**nic**.**pars**.        **172800**    IN    **A**    **72.0.49.5**|ns.**cocca**.**fr**.        **518400**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|
|a.ns.nic.pars.        **172800**    IN    AAAA    2620:171:a01:ad:0:0:0:5|a.ns.nic.pars.        **518400**    IN    AAAA    2620:171:a01:ad:0:0:0:5|
|**b**.ns.nic.pars.        **172800**    IN    A    72.**42**.**113**.5|**a**.ns.nic.pars.        **518400**    IN    A    72.**0**.**49**.5|
|b.ns.nic.pars.        **172800**    IN    AAAA    2620:171:d01:dc:0:0:0:5|b.ns.nic.pars.        **518400**    IN    AAAA    2620:171:d01:dc:0:0:0:5|
||**b.ns.nic.pars.        518400    IN    A    72.42.113.5**|
#
## hkt
|expected|actual|
|--------|---|
|hkt.            86400    IN    DS    **2077** **8** 2 **B467734F0F2A8287BA3A0EDDF252055D740F2FD0072F81095EB6A56BE2405EE0**|hkt.            86400    IN    DS    **23634** **7** **1 9E4E35BC0B5DC9327D0F7042C7ED5FCB043C8CC9**|
|a0.nic.hkt.        **172800**    IN    A    65.22.116.33|**hkt.            86400    IN    DS    23634 7 **2 **0AEABE2C3C77CF919059C8376EC7108E6811BEA78AC731D4347CB15178267428**|
|a0.nic.hkt.        **172800**    IN    AAAA    2a01:8840:72:0:0:0:0:33|a0.nic.hkt.        **518400**    IN    A    65.22.116.33|
|a2.nic.hkt.        **172800**    IN    A    65.22.119.33|a0.nic.hkt.        **518400**    IN    AAAA    2a01:8840:72:0:0:0:0:33|
|a2.nic.hkt.        **172800**    IN    AAAA    2a01:8840:75:0:0:0:0:33|a2.nic.hkt.        **518400**    IN    A    65.22.119.33|
|b0.nic.hkt.        **172800**    IN    A    65.22.117.33|a2.nic.hkt.        **518400**    IN    AAAA    2a01:8840:75:0:0:0:0:33|
|b0.nic.hkt.        **172800**    IN    AAAA    2a01:8840:73:0:0:0:0:33|b0.nic.hkt.        **518400**    IN    A    65.22.117.33|
|c0.nic.hkt.        **172800**    IN    A    65.22.118.33|b0.nic.hkt.        **518400**    IN    AAAA    2a01:8840:73:0:0:0:0:33|
|c0.nic.hkt.        **172800**    IN    AAAA    2a01:8840:74:0:0:0:0:33|c0.nic.hkt.        **518400**    IN    A    65.22.118.33|
||c0.nic.hkt.        **518400**    IN    AAAA    2a01:8840:74:0:0:0:0:33|
#
## afamilycompany
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## allstate
|expected|actual|
|--------|---|
|allstate.        86400    IN    DS    **47509** **8** **2** **101757B35BFEC8D399987D94B495B60ACC0DA525CF92D900C7566BCE6ECF9356**|allstate.        86400    IN    DS    **34735** **7** **1** **25FE3D771952F12DF2FD12032D9260E32E6A0780**|
|**a0.nic.**allstate.    **172800**    IN    **A**    **65.22.48.9**|allstate.        **86400**    IN    **DS**    **34735** **7 2 C1EE5208DB531753E0D94EC79CEC132A4D495D8BC0519A5E3A34913D2510F04C**|
|a0.nic.allstate.    **172800**    IN    AAAA    2a01:8840:2e:0:0:0:0:9|a0.nic.allstate.    **518400**    IN    AAAA    2a01:8840:2e:0:0:0:0:9|
|**a2**.nic.allstate.    **172800**    IN    A    65.22.**51**.9|**a0**.nic.allstate.    **518400**    IN    A    65.22.**48**.9|
|a2.nic.allstate.    **172800**    IN    AAAA    2a01:8840:31:0:0:0:0:9|a2.nic.allstate.    **518400**    IN    AAAA    2a01:8840:31:0:0:0:0:9|
|**b0**.nic.allstate.    **172800**    IN    A    65.22.**49**.9|**a2**.nic.allstate.    **518400**    IN    A    65.22.**51**.9|
|b0.nic.allstate.    **172800**    IN    AAAA    2a01:8840:2f:0:0:0:0:9|b0.nic.allstate.    **518400**    IN    AAAA    2a01:8840:2f:0:0:0:0:9|
|**c0**.nic.allstate.    **172800**    IN    A    65.22.**50**.9|**b0**.nic.allstate.    **518400**    IN    A    65.22.**49**.9|
|c0.nic.allstate.    **172800**    IN    AAAA    2a01:8840:30:0:0:0:0:9|c0.nic.allstate.    **518400**    IN    AAAA    2a01:8840:30:0:0:0:0:9|
||**c0.nic.allstate.    518400    IN    A    65.22.50.9**|
#
## xn--mgbai9azgqp6j
|expected|actual|
|--------|---|
|ns.ntc.net.pk.        **172800**    IN    A    202.83.164.166|ns.ntc.net.pk.        **518400**    IN    A    202.83.164.166|
|ns1.ntc.net.pk.        **172800**    IN    A    202.83.164.167|ns1.ntc.net.pk.        **518400**    IN    A    202.83.164.167|
|ns2.ntc.net.pk.        **172800**    IN    A    175.107.**198**.**150**|ns2.ntc.net.pk.        **518400**    IN    A    175.107.**192**.**11**|
#
## build
|expected|actual|
|--------|---|
|build.            86400    IN    DS    **30770** 8 **2** **68E3857B46D09FE8C87B6144A5D61F9613440A6407331AC598970C29809B56F7**|build.            86400    IN    DS    **54832** 8 **1** **7A463E0B93D57753BF3B3959C080ABDF24BC3843**|
|a.nic.build.        **172800**    IN    A    **194**.**169**.**218**.**20**|a.nic.build.        **518400**    IN    A    **37**.**209**.**192**.**10**|
|a.nic.build.        **172800**    IN    AAAA    **2001:67c:13cc:0:0:0:1:20**|a.nic.build.        **518400**    IN    AAAA    **2001:dcd:1:0:0:0:0:10**|
|b.nic.build.        **172800**    IN    **A**    **185.24.64.20**|b.nic.build.        **518400**    IN    **AAAA**    **2001:dcd:2:0:0:0:0:10**|
|b.nic.build.        **172800**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:20**|b.nic.build.        **518400**    IN    **A**    **37.209.194.10**|
|c.nic.build.        **172800**    IN    **A**    **212.18.248.20**|c.nic.build.        **518400**    IN    **AAAA**    **2001:dcd:3:0:0:0:0:10**|
|c.nic.build.        **172800**    IN    **AAAA**    **2a04:2b00:13ee:0:0:0:0:20**|c.nic.build.        **518400**    IN    **A**    **37.209.196.10**|
|d.nic.build.        **172800**    IN    **A**    **212.18.249.20**|d.nic.build.        **518400**    IN    **AAAA**    **2001:dcd:4:0:0:0:0:10**|
|d.nic.build.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:20**|d.nic.build.        **518400**    IN    **A**    **37.209.198.10**|
#
## redumbrella
|expected|actual|
|--------|---|
|redumbrella.        86400    IN    DS    **44047** **8** 2 **1A8A582FF781CCFA13C4928D373E2F29E7DB7E4027174C68BD7B3E5772EF76C7**|redumbrella.        86400    IN    DS    **29898** **7** **1 5E4B94324C4AAE37080BD1141DFF141037BACDD4**|
|a0.nic.redumbrella.    **172800**    IN    A    65.22.200.1|**redumbrella.        86400    IN    DS    29898 7 **2 **8B3CA8067270B2D8A33DA55FE89323DDEC801609D18435EC2E22995D13809EDA**|
|a0.nic.redumbrella.    **172800**    IN    AAAA    2a01:8840:c2:0:0:0:0:1|a0.nic.redumbrella.    **518400**    IN    A    65.22.200.1|
|a2.nic.redumbrella.    **172800**    IN    AAAA    2a01:8840:c5:0:0:0:0:1|a0.nic.redumbrella.    **518400**    IN    AAAA    2a01:8840:c2:0:0:0:0:1|
|a2.nic.redumbrella.    **172800**    IN    A    65.22.203.1|a2.nic.redumbrella.    **518400**    IN    AAAA    2a01:8840:c5:0:0:0:0:1|
|b0.nic.redumbrella.    **172800**    IN    A    65.22.201.1|a2.nic.redumbrella.    **518400**    IN    A    65.22.203.1|
|b0.nic.redumbrella.    **172800**    IN    AAAA    2a01:8840:c3:0:0:0:0:1|b0.nic.redumbrella.    **518400**    IN    A    65.22.201.1|
|c0.nic.redumbrella.    **172800**    IN    **A**    **65.22.202.1**|b0.nic.redumbrella.    **518400**    IN    AAAA    2a01:8840:c3:0:0:0:0:1|
|c0.nic.redumbrella.    **172800**    IN    **AAAA**    **2a01:8840:c4:0:0:0:0:1**|c0.nic.redumbrella.    **518400**    IN    **AAAA**    **2a01:8840:c4:0:0:0:0:1**|
||c0.nic.redumbrella.    **518400**    IN    **A**    **65.22.202.1**|
#
## sbi
|expected|actual|
|--------|---|
|sbi.            86400    IN    DS    **31606** **8** 2 **70193B642AEFE13270D7FF55A3FD26BCB1C6CDF4D43B04F694509DE430381F4B**|sbi.            86400    IN    DS    **52755** **7** **1 4AA48D9EED8EE9F780FC29C1AE06AF0DF013DDDC**|
|a0.nic.sbi.        **172800**    IN    A    65.22.176.9|**sbi.            86400    IN    DS    52755 7 **2 **A9A05829C13FBE142E4388FEFA7A0AC7318E807C6C1A9C589E956EBA9433D941**|
|a0.nic.sbi.        **172800**    IN    AAAA    2a01:8840:aa:0:0:0:0:9|a0.nic.sbi.        **518400**    IN    A    65.22.176.9|
|a2.nic.sbi.        **172800**    IN    A    65.22.179.9|a0.nic.sbi.        **518400**    IN    AAAA    2a01:8840:aa:0:0:0:0:9|
|a2.nic.sbi.        **172800**    IN    AAAA    2a01:8840:ad:0:0:0:0:9|a2.nic.sbi.        **518400**    IN    A    65.22.179.9|
|b0.nic.sbi.        **172800**    IN    A    65.22.177.9|a2.nic.sbi.        **518400**    IN    AAAA    2a01:8840:ad:0:0:0:0:9|
|**b0**.nic.sbi.        **172800**    IN    AAAA    **2a01:8840:ab:0:0:0:0:9**|b0.nic.sbi.        **518400**    IN    **AAAA    2a01:8840:ab:0:0:0:0:9**|
|c0.nic.sbi.        **172800**    IN    A    65.22.178.9|**b0.nic.sbi.        518400    IN    **A    65.22.177.9|
|**c0.nic.sbi.        172800    IN    AAAA    2a01:8840:ac:0:0:0:0:9**|**c0**.nic.sbi.        **518400**    IN    AAAA    **2a01:8840:ac:0:0:0:0:9**|
||c0.nic.sbi.        **518400**    IN    A    65.22.178.9|
#
## vanguard
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bugatti
|expected|actual|
|--------|---|
|**bugatti.        86400    IN    DS    50856 7 2 A0F3CF5BBA33BC0A12260817A8D9A8CE9B469007D5DE054F80B23C8AF9DD709E**||
|a0.nic.bugatti.        **172800**    IN    A    65.22.208.9|a0.nic.bugatti.        **518400**    IN    A    65.22.208.9|
|a0.nic.bugatti.        **172800**    IN    AAAA    2a01:8840:ca:0:0:0:0:9|a0.nic.bugatti.        **518400**    IN    AAAA    2a01:8840:ca:0:0:0:0:9|
|a2.nic.bugatti.        **172800**    IN    A    65.22.211.9|a2.nic.bugatti.        **518400**    IN    A    65.22.211.9|
|a2.nic.bugatti.        **172800**    IN    AAAA    2a01:8840:cd:0:0:0:0:9|a2.nic.bugatti.        **518400**    IN    AAAA    2a01:8840:cd:0:0:0:0:9|
|b0.nic.bugatti.        **172800**    IN    A    65.22.209.9|b0.nic.bugatti.        **518400**    IN    A    65.22.209.9|
|b0.nic.bugatti.        **172800**    IN    AAAA    2a01:8840:cb:0:0:0:0:9|b0.nic.bugatti.        **518400**    IN    AAAA    2a01:8840:cb:0:0:0:0:9|
|c0.nic.bugatti.        **172800**    IN    **A**    **65.22.210.9**|c0.nic.bugatti.        **518400**    IN    **AAAA**    **2a01:8840:cc:0:0:0:0:9**|
|c0.nic.bugatti.        **172800**    IN    **AAAA**    **2a01:8840:cc:0:0:0:0:9**|c0.nic.bugatti.        **518400**    IN    **A**    **65.22.210.9**|
#
## asda
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sbs
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sca
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--cg4bki
|expected|actual|
|--------|---|
||**xn--cg4bki.        172800    IN    NS    a.xn--cg4bki.dyntld.net.**|
||**xn--cg4bki.        172800    IN    NS    b.xn--cg4bki.dyntld.net.**|
||**xn--cg4bki.        172800    IN    NS    c.xn--cg4bki.dyntld.net.**|
||**xn--cg4bki.        172800    IN    NS    d.xn--cg4bki.dyntld.net.**|
|ns1.xn--cg4bki.centralnic-dns.com.    **172800**    IN    A    194.169.218.113|ns1.xn--cg4bki.centralnic-dns.com.    **518400**    IN    A    194.169.218.113|
|ns1.xn--cg4bki.centralnic-dns.com.    **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:113|ns1.xn--cg4bki.centralnic-dns.com.    **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:113|
|ns2.xn--cg4bki.centralnic-dns.com.    **172800**    IN    A    185.24.64.113|ns2.xn--cg4bki.centralnic-dns.com.    **518400**    IN    A    185.24.64.113|
|ns2.xn--cg4bki.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:113|ns2.xn--cg4bki.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:113|
|ns3.xn--cg4bki.centralnic-dns.com.    **172800**    IN    A    212.18.248.113|ns3.xn--cg4bki.centralnic-dns.com.    **518400**    IN    A    212.18.248.113|
|ns3.xn--cg4bki.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:113|ns3.xn--cg4bki.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:113|
|ns4.xn--cg4bki.centralnic-dns.com.    **172800**    IN    A    212.18.249.113|ns4.xn--cg4bki.centralnic-dns.com.    **518400**    IN    A    212.18.249.113|
|ns4.xn--cg4bki.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:113|ns4.xn--cg4bki.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:113|
||**a.xn--cg4bki.dyntld.net.    518400    IN    A    162.88.40.1**|
||**a.xn--cg4bki.dyntld.net.    518400    IN    AAAA    2600:2000:3010:0:0:0:0:1**|
||**b.xn--cg4bki.dyntld.net.    518400    IN    AAAA    2600:2000:3011:0:0:0:0:1**|
||**b.xn--cg4bki.dyntld.net.    518400    IN    A    162.88.41.1**|
||**c.xn--cg4bki.dyntld.net.    518400    IN    AAAA    2600:2000:3012:0:0:0:0:1**|
||**c.xn--cg4bki.dyntld.net.    518400    IN    A    162.88.42.1**|
||**d.xn--cg4bki.dyntld.net.    518400    IN    A    162.88.43.1**|
||**d.xn--cg4bki.dyntld.net.    518400    IN    AAAA    2600:2000:3013:0:0:0:0:1**|
#
## stada
|expected|actual|
|--------|---|
|**stada.            86400    IN    DS    13276 7 2 A00290E911B2307036A42446921089D3E12708167D8ED195E156391BAAAF7899**||
|a0.nic.stada.        **172800**    IN    **A**    **65.22.156.25**|a0.nic.stada.        **518400**    IN    **AAAA**    **2a01:8840:9a:0:0:0:0:25**|
|a0.nic.stada.        **172800**    IN    **AAAA**    **2a01:8840:9a:0:0:0:0:25**|a0.nic.stada.        **518400**    IN    **A**    **65.22.156.25**|
|a2.nic.stada.        **172800**    IN    A    65.22.159.25|a2.nic.stada.        **518400**    IN    A    65.22.159.25|
|a2.nic.stada.        **172800**    IN    AAAA    2a01:8840:9d:0:0:0:0:25|a2.nic.stada.        **518400**    IN    AAAA    2a01:8840:9d:0:0:0:0:25|
|b0.nic.stada.        **172800**    IN    A    65.22.157.25|b0.nic.stada.        **518400**    IN    A    65.22.157.25|
|b0.nic.stada.        **172800**    IN    AAAA    2a01:8840:9b:0:0:0:0:25|b0.nic.stada.        **518400**    IN    AAAA    2a01:8840:9b:0:0:0:0:25|
|c0.nic.stada.        **172800**    IN    A    65.22.158.25|c0.nic.stada.        **518400**    IN    A    65.22.158.25|
|c0.nic.stada.        **172800**    IN    AAAA    2a01:8840:9c:0:0:0:0:25|c0.nic.stada.        **518400**    IN    AAAA    2a01:8840:9c:0:0:0:0:25|
#
## fiat
|expected|actual|
|--------|---|
|fiat.            86400    IN    DS    **1339** **8** 2 **4BBBFF995D2B4CF8E709DEC8BE78CA00B480DDF6C2C1D7879041E79F8E9D04B8**|fiat.            86400    IN    DS    **22158** **7** **1 66E6FCF72DCABF00E09ED09AE18CB6F78F184774**|
|a0.nic.fiat.        **172800**    IN    **A**    **65.22.124.1**|**fiat.            86400    IN    DS    22158 7 **2 **E8A59D826789180190382764195E981DFFBE1E35E799BE3490ADDBAE7305C309**|
|a0.nic.fiat.        **172800**    IN    **AAAA**    **2a01:8840:7a:0:0:0:0:1**|a0.nic.fiat.        **518400**    IN    **AAAA**    **2a01:8840:7a:0:0:0:0:1**|
|a2.nic.fiat.        **172800**    IN    A    65.22.127.1|a0.nic.fiat.        **518400**    IN    **A**    **65.22.124.1**|
|a2.nic.fiat.        **172800**    IN    AAAA    2a01:8840:7d:0:0:0:0:1|a2.nic.fiat.        **518400**    IN    A    65.22.127.1|
|b0.nic.fiat.        **172800**    IN    A    65.22.125.1|a2.nic.fiat.        **518400**    IN    AAAA    2a01:8840:7d:0:0:0:0:1|
|b0.nic.fiat.        **172800**    IN    AAAA    2a01:8840:7b:0:0:0:0:1|b0.nic.fiat.        **518400**    IN    A    65.22.125.1|
|c0.nic.fiat.        **172800**    IN    A    65.22.126.1|b0.nic.fiat.        **518400**    IN    AAAA    2a01:8840:7b:0:0:0:0:1|
|c0.nic.fiat.        **172800**    IN    AAAA    2a01:8840:7c:0:0:0:0:1|c0.nic.fiat.        **518400**    IN    A    65.22.126.1|
||c0.nic.fiat.        **518400**    IN    AAAA    2a01:8840:7c:0:0:0:0:1|
#
## ac
|expected|actual|
|--------|---|
||**ac.            86400    IN    DS    42665 8 1 D5E99D85351D361BD6B5B1582F634E8A85CF1BF7**|
|a0.nic.ac.        **172800**    IN    A    65.22.160.1|a0.nic.ac.        **518400**    IN    A    65.22.160.1|
|a0.nic.ac.        **172800**    IN    AAAA    2a01:8840:9e:0:0:0:0:1|a0.nic.ac.        **518400**    IN    AAAA    2a01:8840:9e:0:0:0:0:1|
|a2.nic.ac.        **172800**    IN    A    65.22.163.1|a2.nic.ac.        **518400**    IN    **AAAA    2a01:8840:a1:0:0:0:0:1**|
|**a2**.nic.ac.        **172800**    IN    AAAA    **2a01:8840:a1:0:0:0:0:1**|**a2.nic.ac.        518400    IN    **A    65.22.163.1|
|b0.nic.ac.        **172800**    IN    A    65.22.161.1|**b0**.nic.ac.        **518400**    IN    AAAA    **2a01:8840:9f:0:0:0:0:1**|
|**b0.nic.ac.        172800    IN    AAAA    2a01:8840:9f:0:0:0:0:1**|b0.nic.ac.        **518400**    IN    A    65.22.161.1|
|c0.nic.ac.        **172800**    IN    A    65.22.162.1|c0.nic.ac.        **518400**    IN    A    65.22.162.1|
|c0.nic.ac.        **172800**    IN    AAAA    2a01:8840:a0:0:0:0:0:1|c0.nic.ac.        **518400**    IN    AAAA    2a01:8840:a0:0:0:0:0:1|
#
## ad
|expected|actual|
|--------|---|
|**ad.            172800    IN    NS    ad.ns.nic.es.**||
|ad.            172800    IN    NS    **ns3**.nic.**fr**.|ad.            172800    IN    NS    **ad**.**ns.**nic.**es**.|
|ad.            **86400**    IN    **DS**    **2095** **8 1 7D85B92A436D6FA5D4CD7BC7371842514F57F665**|ad.            **172800**    IN    **NS**    **ns3.nic.fr.**|
|ad.            86400    IN    DS    **2095** 8 2 **9FF1BFB9A28C1811152149807F608C222F97CA85764323F4C4403C8C7F5931E2**|ad.            86400    IN    DS    **60892** 8 2 **90C3C642C6EB60EAC3C982ED697339A8EE3F70AEA644AC185BD9997790AFABC4**|
|ad.            86400    IN    DS    **61909** 8 1 **27209E62E4F85159D47D17B1B3691A49253638A6**|ad.            86400    IN    DS    **60892** 8 1 **A107006ADE4CA8B6381660A96A606E20B13E2546**|
|**dnsc.**ad.        **172800**    IN    **A**    **194.158.74.10**|ad.            **86400**    IN    **DS**    **61909** **8 1 27209E62E4F85159D47D17B1B3691A49253638A6**|
|dnsc.ad.        **172800**    IN    AAAA    2a02:8060:32fa:0:0:0:0:b|dnsc.ad.        **518400**    IN    AAAA    2a02:8060:32fa:0:0:0:0:b|
|**dnsm**.ad.        **172800**    IN    A    194.158.74.**9**|**dnsc**.ad.        **518400**    IN    A    194.158.74.**10**|
|dnsm.ad.        **172800**    IN    AAAA    2a02:8060:32fa:0:0:0:0:a|dnsm.ad.        **518400**    IN    AAAA    2a02:8060:32fa:0:0:0:0:a|
|ad.ns.nic.es.        **172800**    IN    A    194.69.254.15|**dnsm.**ad.**        518400    IN    A    194.158.74.9**|
|ns3.nic.fr.        **172800**    IN    A    192.134.0.49|**ad.**ns.nic.es.        **518400**    IN    A    194.69.254.15|
|ns3.nic.fr.        **172800**    IN    AAAA    2001:660:3006:1:0:0:1:1|ns3.nic.fr.        **518400**    IN    A    192.134.0.49|
|ad.cctld.authdns.ripe.net.    **172800**    IN    A    193.0.9.53|ns3.nic.fr.        **518400**    IN    AAAA    2001:660:3006:1:0:0:1:1|
|ad.cctld.authdns.ripe.net.    **172800**    IN    AAAA    2001:67c:e0:0:0:0:0:53|ad.cctld.authdns.ripe.net.    **518400**    IN    A    193.0.9.53|
||ad.cctld.authdns.ripe.net.    **518400**    IN    AAAA    2001:67c:e0:0:0:0:0:53|
#
## af
|expected|actual|
|--------|---|
|**af.            172800    IN    NS    ns.cocca.fr.**||
||**af.            172800    IN    NS    ns.cocca.fr.**|
|ns.anycast.nic.af.    **172800**    IN    A    204.61.216.13|ns.anycast.nic.af.    **518400**    IN    A    204.61.216.13|
|ns.anycast.nic.af.    **172800**    IN    AAAA    2001:500:14:6013:ad:0:0:1|ns.anycast.nic.af.    **518400**    IN    AAAA    2001:500:14:6013:ad:0:0:1|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
||**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
#
## ag
|expected|actual|
|--------|---|
|**ag.            86400    IN    DS    24316 7 2 D8744AA75E4005D2D1C2D01BE95D173D71D4C54663C245EC17770DE08FCBE1C5**||
|a0.cctld.afilias-nst.info.    **172800**    IN    A    199.254.59.1|a0.cctld.afilias-nst.info.    **518400**    IN    A    199.254.59.1|
|a0.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:1|a0.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:1|
|a2.cctld.afilias-nst.info.    **172800**    IN    A    199.249.116.1|a2.cctld.afilias-nst.info.    **518400**    IN    A    199.249.116.1|
|a2.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:1|a2.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **A**    **199.254.61.1**|c0.cctld.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|
|c0.cctld.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|c0.cctld.afilias-nst.info.    **518400**    IN    **A**    **199.254.61.1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.60.1|b0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.60.1|
|b0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:26:0:0:0:0:1|b0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:26:0:0:0:0:1|
|b2.cctld.afilias-nst.org.    **172800**    IN    A    199.249.124.1|b2.cctld.afilias-nst.org.    **518400**    IN    A    199.249.124.1|
|b2.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4c:0:0:0:0:1|b2.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4c:0:0:0:0:1|
|d0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.62.1|d0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.62.1|
|d0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:1|d0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:1|
#
## ai
|expected|actual|
|--------|---|
|pch.whois.ai.        **172800**    IN    A    204.61.216.123|**ai.            86400    IN    DS    1657 8 1 0B0D56361CE62118537E07A680E9582F5F5FA129**|
|pch.whois.ai.        **172800**    IN    AAAA    2001:500:14:6123:ad:0:0:1|pch.whois.ai.        **518400**    IN    A    204.61.216.123|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|pch.whois.ai.        **518400**    IN    AAAA    2001:500:14:6123:ad:0:0:1|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
||ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
||**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
#
## bbt
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## abbott
|expected|actual|
|--------|---|
|**abbott.            86400    IN    DS    55506 7 2 D009CCCE47BE86B22F8ADB780FF5D4C3F91A883D18B00A37F42E17372FFC1D67**|a0.nic.abbott.        **518400**    IN    A    65.22.156.41|
|a0.nic.abbott.        **172800**    IN    A    65.22.156.41|a0.nic.abbott.        **518400**    IN    AAAA    2a01:8840:9a:0:0:0:0:41|
|a0.nic.abbott.        **172800**    IN    AAAA    2a01:8840:9a:0:0:0:0:41|a2.nic.abbott.        **518400**    IN    A    65.22.159.41|
|a2.nic.abbott.        **172800**    IN    A    65.22.159.41|a2.nic.abbott.        **518400**    IN    AAAA    2a01:8840:9d:0:0:0:0:41|
|a2.nic.abbott.        **172800**    IN    AAAA    2a01:8840:9d:0:0:0:0:41|b0.nic.abbott.        **518400**    IN    **AAAA**    **2a01:8840:9b:0:0:0:0:41**|
|b0.nic.abbott.        **172800**    IN    **A**    **65.22.157.41**|b0.nic.abbott.        **518400**    IN    **A**    **65.22.157.41**|
|b0.nic.abbott.        **172800**    IN    **AAAA**    **2a01:8840:9b:0:0:0:0:41**|c0.nic.abbott.        **518400**    IN    A    65.22.158.41|
|c0.nic.abbott.        **172800**    IN    A    65.22.158.41|c0.nic.abbott.        **518400**    IN    AAAA    2a01:8840:9c:0:0:0:0:41|
|c0.nic.abbott.        **172800**    IN    AAAA    2a01:8840:9c:0:0:0:0:41||
#
## be
|expected|actual|
|--------|---|
||**be.            86400    IN    DS    12664 8 1 59462E9CB5520A36DD248D9DDC4EAA44672A5ED1**|
||**be.            86400    IN    DS    52756 8 1 6047D5E44427530D6BE989ED58CAFC9A881F2810**|
|a.ns.dns.be.        **172800**    IN    A    194.0.6.1|a.ns.dns.be.        **518400**    IN    A    194.0.6.1|
|a.ns.dns.be.        **172800**    IN    AAAA    2001:678:9:0:0:0:0:1|a.ns.dns.be.        **518400**    IN    AAAA    2001:678:9:0:0:0:0:1|
|b.ns.dns.be.        **172800**    IN    A    194.0.37.1|b.ns.dns.be.        **518400**    IN    **AAAA    2001:678:64:0:0:0:0:1**|
|**b**.ns.dns.be.        **172800**    IN    AAAA    **2001:678:64:0:0:0:0:1**|**b.ns.dns.be.        518400    IN    **A    194.0.37.1|
|c.ns.dns.be.        **172800**    IN    A    194.0.43.1|**c**.ns.dns.be.        **518400**    IN    AAAA    **2001:678:68:0:0:0:0:1**|
|**c**.ns.dns.be.        **172800**    IN    AAAA    **2001:678:68:0:0:0:0:1**|c.ns.dns.be.        **518400**    IN    A    194.0.43.1|
|d.ns.dns.be.        **172800**    IN    A    194.0.44.1|**d**.ns.dns.be.        **518400**    IN    AAAA    **2001:678:6c:0:0:0:0:1**|
|**d.ns.dns.be.        172800    IN    AAAA    2001:678:6c:0:0:0:0:1**|d.ns.dns.be.        **518400**    IN    A    194.0.44.1|
|y.ns.dns.be.        **172800**    IN    A    120.29.253.8|y.ns.dns.be.        **518400**    IN    A    120.29.253.8|
|y.ns.dns.be.        **172800**    IN    AAAA    2001:dcd:7:0:0:0:0:8|y.ns.dns.be.        **518400**    IN    AAAA    2001:dcd:7:0:0:0:0:8|
|z.nsset.be.        **172800**    IN    **A**    **194.0.25.36**|z.nsset.be.        **518400**    IN    **AAAA**    **2001:678:20:0:0:0:0:36**|
|z.nsset.be.        **172800**    IN    **AAAA**    **2001:678:20:0:0:0:0:36**|z.nsset.be.        **518400**    IN    **A**    **194.0.25.36**|
#
## bf
|expected|actual|
|--------|---|
|**bf.            172800    IN    NS    a.registre.bf.**||
|**bf.            172800    IN    NS    nahouri.onatel.bf.**||
|nahouri.onatel.bf.    172800    IN    **A**    **206**.**82**.**130**.**196**|**bf.            172800    IN    NS    **nahouri.onatel.bf.|
|**a**.**registre**.bf.        **172800**    IN    A    **212**.**52**.**146**.**50**|**bf.            **172800    IN    **NS**    **ns-bf**.**afrinic**.**net**.|
|censvrns0001.ird.fr.    **172800**    IN    A    91.203.32.147|**nahouri**.**onatel**.bf.    **518400**    IN    A    **206**.**82**.**130**.**196**|
||censvrns0001.ird.fr.    **518400**    IN    A    91.203.32.147|
||**ns-bf.afrinic.net.    518400    IN    A    196.216.168.34**|
||**ns-bf.afrinic.net.    518400    IN    AAAA    2001:43f8:120:0:0:0:0:34**|
#
## bcg
|expected|actual|
|--------|---|
|bcg.            86400    IN    DS    **10891** **8** 2 **E3428A6F71B3F25036A32EAFB4811EE26D0E4C2F9E1098C0071AB25431CB339D**|bcg.            86400    IN    DS    **48108** **7** **1 1FCAB02E25C47F8C985A150F983DC199D3E6B9BE**|
|a0.nic.bcg.        **172800**    IN    A    65.22.216.25|**bcg.            86400    IN    DS    48108 7 **2 **E085676A3B8056349653315E5DF6709BB16844BA1DBD701517FFEA8B79F7A32E**|
|a0.nic.bcg.        **172800**    IN    AAAA    2a01:8840:d2:0:0:0:0:25|a0.nic.bcg.        **518400**    IN    A    65.22.216.25|
|a2.nic.bcg.        **172800**    IN    **A**    **65.22.219.25**|a0.nic.bcg.        **518400**    IN    AAAA    2a01:8840:d2:0:0:0:0:25|
|a2.nic.bcg.        **172800**    IN    **AAAA**    **2a01:8840:d5:0:0:0:0:25**|a2.nic.bcg.        **518400**    IN    **AAAA**    **2a01:8840:d5:0:0:0:0:25**|
|b0.nic.bcg.        **172800**    IN    A    65.22.217.25|a2.nic.bcg.        **518400**    IN    **A**    **65.22.219.25**|
|b0.nic.bcg.        **172800**    IN    AAAA    2a01:8840:d3:0:0:0:0:25|b0.nic.bcg.        **518400**    IN    A    65.22.217.25|
|c0.nic.bcg.        **172800**    IN    **A**    **65.22.218.25**|b0.nic.bcg.        **518400**    IN    AAAA    2a01:8840:d3:0:0:0:0:25|
|c0.nic.bcg.        **172800**    IN    **AAAA**    **2a01:8840:d4:0:0:0:0:25**|c0.nic.bcg.        **518400**    IN    **AAAA**    **2a01:8840:d4:0:0:0:0:25**|
||c0.nic.bcg.        **518400**    IN    **A**    **65.22.218.25**|
#
## bj
|expected|actual|
|--------|---|
|ns1.nic.bj.        **172800**    IN    A    154.65.31.84|ns1.nic.bj.        **518400**    IN    A    154.65.31.84|
|ns2.nic.bj.        **172800**    IN    A    41.85.191.2|ns2.nic.bj.        **518400**    IN    A    41.85.191.2|
|pch.nic.bj.        **172800**    IN    A    204.61.216.125|pch.nic.bj.        **518400**    IN    A    204.61.216.125|
|pch.nic.bj.        **172800**    IN    AAAA    2001:500:14:6125:ad:0:0:1|pch.nic.bj.        **518400**    IN    AAAA    2001:500:14:6125:ad:0:0:1|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
||**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
#
## xn--4gbrim
|expected|actual|
|--------|---|
|xn--4gbrim.        86400    IN    DS    **38332** **8** 2 **14E1F26F8B51F92BD671DBE97F651903FA1F26DF07E2E882DD997A1D73971426**|xn--4gbrim.        86400    IN    DS    **21430** **7** **1 C4DA13C32BDC30090E91AD6889D5137EF1097FFF**|
|a0.nic.xn--4gbrim.    **172800**    IN    A    65.22.244.33|**xn--4gbrim.        86400    IN    DS    21430 7 **2 **10EB900D8A6D23890EF9200A8C149FDB0D412A7137E78C58F89B07C66DC50B25**|
|a0.nic.xn--4gbrim.    **172800**    IN    AAAA    2a01:8840:ee:0:0:0:0:33|a0.nic.xn--4gbrim.    **518400**    IN    A    65.22.244.33|
|a2.nic.xn--4gbrim.    **172800**    IN    **A**    **65.22.247.33**|a0.nic.xn--4gbrim.    **518400**    IN    AAAA    2a01:8840:ee:0:0:0:0:33|
|a2.nic.xn--4gbrim.    **172800**    IN    **AAAA**    **2a01:8840:f1:0:0:0:0:33**|a2.nic.xn--4gbrim.    **518400**    IN    **AAAA**    **2a01:8840:f1:0:0:0:0:33**|
|b0.nic.xn--4gbrim.    **172800**    IN    A    65.22.245.33|a2.nic.xn--4gbrim.    **518400**    IN    **A**    **65.22.247.33**|
|b0.nic.xn--4gbrim.    **172800**    IN    AAAA    2a01:8840:ef:0:0:0:0:33|b0.nic.xn--4gbrim.    **518400**    IN    A    65.22.245.33|
|c0.nic.xn--4gbrim.    **172800**    IN    **A**    **65.22.246.33**|b0.nic.xn--4gbrim.    **518400**    IN    AAAA    2a01:8840:ef:0:0:0:0:33|
|c0.nic.xn--4gbrim.    **172800**    IN    **AAAA**    **2a01:8840:f0:0:0:0:0:33**|c0.nic.xn--4gbrim.    **518400**    IN    **AAAA**    **2a01:8840:f0:0:0:0:0:33**|
||c0.nic.xn--4gbrim.    **518400**    IN    **A**    **65.22.246.33**|
#
## bm
|expected|actual|
|--------|---|
||**bm.            86400    IN    DS    37810 8 1 E75D8FC16E852CA8E77D478CD1C43789907D651F**|
|a0.bm.afilias-nst.info.    **172800**    IN    **A**    **199.254.59.9**|a0.bm.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:25:0:0:0:0:9**|
|a0.bm.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:25:0:0:0:0:9**|a0.bm.afilias-nst.info.    **518400**    IN    **A**    **199.254.59.9**|
|a2.bm.afilias-nst.info.    **172800**    IN    A    199.249.116.9|a2.bm.afilias-nst.info.    **518400**    IN    A    199.249.116.9|
|a2.bm.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:9|a2.bm.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:9|
|c0.bm.afilias-nst.info.    **172800**    IN    A    199.254.61.9|c0.bm.afilias-nst.info.    **518400**    IN    A    199.254.61.9|
|c0.bm.afilias-nst.info.    **172800**    IN    AAAA    2001:500:27:0:0:0:0:9|c0.bm.afilias-nst.info.    **518400**    IN    AAAA    2001:500:27:0:0:0:0:9|
|b0.bm.afilias-nst.org.    **172800**    IN    A    199.254.60.9|b0.bm.afilias-nst.org.    **518400**    IN    **AAAA    2001:500:26:0:0:0:0:9**|
|**b0**.bm.afilias-nst.org.    **172800**    IN    AAAA    **2001:500:26:0:0:0:0:9**|**b0.bm.afilias-nst.org.    518400    IN    **A    199.254.60.9|
|b2.bm.afilias-nst.org.    **172800**    IN    A    199.249.124.9|**b2**.bm.afilias-nst.org.    **518400**    IN    AAAA    **2001:500:4c:0:0:0:0:9**|
|**b2.bm.afilias-nst.org.    172800    IN    AAAA    2001:500:4c:0:0:0:0:9**|b2.bm.afilias-nst.org.    **518400**    IN    A    199.249.124.9|
|d0.bm.afilias-nst.org.    **172800**    IN    A    199.254.62.9|d0.bm.afilias-nst.org.    **518400**    IN    A    199.254.62.9|
|d0.bm.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:9|d0.bm.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:9|
#
## sanofi
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bz
|expected|actual|
|--------|---|
|bz.            86400    IN    DS    **22882** **8** 2 **088AD52A5E8E9ADF54345CB21753A54F71BFB8E2674F08B02B64AB53F45EAB9F**|bz.            86400    IN    DS    **16455** **7** **1 409AA5CD776352AEAB7A46B64EE7BA8061CB9374**|
|a0.cctld.afilias-nst.info.    **172800**    IN    A    199.254.59.1|**bz.            86400    IN    DS    16455 7 **2 **457C64669C357AF4AABDEB16A6A119B22D3FCB339BBF3C1701AA84CBC3E105F3**|
|a0.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:1|a0.cctld.afilias-nst.info.    **518400**    IN    A    199.254.59.1|
|a2.cctld.afilias-nst.info.    **172800**    IN    A    199.249.116.1|a0.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:1|
|a2.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:1|a2.cctld.afilias-nst.info.    **518400**    IN    A    199.249.116.1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **A**    **199.254.61.1**|a2.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|c0.cctld.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.60.1|c0.cctld.afilias-nst.info.    **518400**    IN    **A**    **199.254.61.1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:26:0:0:0:0:1|b0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.60.1|
|b2.cctld.afilias-nst.org.    **172800**    IN    A    199.249.124.1|b0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:26:0:0:0:0:1|
|b2.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4c:0:0:0:0:1|b2.cctld.afilias-nst.org.    **518400**    IN    A    199.249.124.1|
|d0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.62.1|b2.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4c:0:0:0:0:1|
|d0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:1|d0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.62.1|
||d0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:1|
#
## xn--mgbx4cd0ab
|expected|actual|
|--------|---|
|**xn--mgbx4cd0ab.        172800    IN    NS    a.nic.my.**||
||**xn--mgbx4cd0ab.        172800    IN    NS    a.nic.my.**|
||**xn--mgbx4cd0ab.        172800    IN    NS    a1.mynic.my.**|
|**xn--mgbx4cd0ab.        172800    IN    NS    a1.nic.my.**||
|**xn--mgbx4cd0ab.        86400    IN    DS    1998 8 1 60C87D53F741F6452301D8BB42D6A09081E2B71D**||
|**xn--mgbx4cd0ab.        86400    IN    DS    1998 8 2 DE4C45D877C64E9C3EBCBC79BADBC104D7C5292D72BC6CA47090B31BE24212E0**||
|**xn--mgbx4cd0ab.        86400    IN    DS    37866 8 1 071FEAC6220886F105BDC32346548DEAC4A0DB37**||
|a.mynic.centralnic-dns.com.    **172800**    IN    A    194.169.218.114|**xn--mgbx4cd0ab.        86400    IN    DS    1998 8 2 DE4C45D877C64E9C3EBCBC79BADBC104D7C5292D72BC6CA47090B31BE24212E0**|
|a.mynic.centralnic-dns.com.    **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:114|**xn--mgbx4cd0ab.        86400    IN    DS    37866 8 1 071FEAC6220886F105BDC32346548DEAC4A0DB37**|
|b.mynic.centralnic-dns.com.    **172800**    IN    **A**    **185.24.64.114**|**xn--mgbx4cd0ab.        86400    IN    DS    1998 8 1 60C87D53F741F6452301D8BB42D6A09081E2B71D**|
|b.mynic.centralnic-dns.com.    **172800**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:114**|a.mynic.centralnic-dns.com.    **518400**    IN    A    194.169.218.114|
|c.mynic.centralnic-dns.com.    **172800**    IN    A    212.18.248.114|a.mynic.centralnic-dns.com.    **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:114|
|c.mynic.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:114|b.mynic.centralnic-dns.com.    **518400**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:114**|
|d.mynic.centralnic-dns.com.    **172800**    IN    A    212.18.249.114|b.mynic.centralnic-dns.com.    **518400**    IN    **A**    **185.24.64.114**|
|d.mynic.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:114|c.mynic.centralnic-dns.com.    **518400**    IN    A    212.18.248.114|
|**a**.**nic**.my.        **172800**    IN    A    **103**.**44**.**108**.**53**|c.mynic.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:114|
|a.nic.my.        **172800**    IN    AAAA    2001:ddc:0:53:0:0:0:53|d.mynic.centralnic-dns.com.    **518400**    IN    A    212.18.249.114|
|**a1**.nic.my.        **172800**    IN    A    **202**.**171**.**47**.**204**|d.mynic.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:114|
||**a1**.**mynic**.my.        **518400**    IN    A    **202**.**171**.**47**.**204**|
||a.nic.my.        **518400**    IN    AAAA    2001:ddc:0:53:0:0:0:53|
||**a**.nic.my.        **518400**    IN    A    **103**.**44**.**108**.**53**|
#
## xn--i1b6b1a6a2e
|expected|actual|
|--------|---|
|xn--i1b6b1a6a2e.    86400    IN    DS    **45889** **8** **2** **1EF7ACA91F4EF292F518F1FCF77A646C21D7AA2594E3BD4AF18906AF70774604**|xn--i1b6b1a6a2e.    86400    IN    DS    **16573** **7** **1** **7C1A115977DAD3C59987490274854E013D8B5FCE**|
|**a0.nic.**xn--i1b6b1a6a2e.    **172800**    IN    **A**    **65.22.184.1**|xn--i1b6b1a6a2e.    **86400**    IN    **DS**    **16573** **7 2 811CF69D0FA4F6337B5F5488E243E2401B53D6058F041532B24525DDCA4FD35C**|
|a0.nic.xn--i1b6b1a6a2e.    **172800**    IN    AAAA    2a01:8840:b2:0:0:0:0:1|a0.nic.xn--i1b6b1a6a2e.    **518400**    IN    AAAA    2a01:8840:b2:0:0:0:0:1|
|**a2**.nic.xn--i1b6b1a6a2e.    **172800**    IN    A    65.22.**187**.1|**a0**.nic.xn--i1b6b1a6a2e.    **518400**    IN    A    65.22.**184**.1|
|a2.nic.xn--i1b6b1a6a2e.    **172800**    IN    **AAAA**    **2a01:8840:b5:0:0:0:0:1**|a2.nic.xn--i1b6b1a6a2e.    **518400**    IN    **A**    **65.22.187.1**|
|**b0**.nic.xn--i1b6b1a6a2e.    **172800**    IN    **A**    **65.22.185.1**|**a2**.nic.xn--i1b6b1a6a2e.    **518400**    IN    **AAAA**    **2a01:8840:b5:0:0:0:0:1**|
|b0.nic.xn--i1b6b1a6a2e.    **172800**    IN    AAAA    2a01:8840:b3:0:0:0:0:1|b0.nic.xn--i1b6b1a6a2e.    **518400**    IN    AAAA    2a01:8840:b3:0:0:0:0:1|
|**c0**.nic.xn--i1b6b1a6a2e.    **172800**    IN    A    65.22.**186**.1|**b0**.nic.xn--i1b6b1a6a2e.    **518400**    IN    A    65.22.**185**.1|
|c0.nic.xn--i1b6b1a6a2e.    **172800**    IN    AAAA    2a01:8840:b4:0:0:0:0:1|c0.nic.xn--i1b6b1a6a2e.    **518400**    IN    AAAA    2a01:8840:b4:0:0:0:0:1|
||**c0.nic.xn--i1b6b1a6a2e.    518400    IN    A    65.22.186.1**|
#
## sohu
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## cc
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ses
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sew
|expected|actual|
|--------|---|
|sew.            86400    IN    DS    **24562** **8** 2 **F058B69DC4842232E352DBE1485DFC257AD1627AEE9F4BF4DECD967307E30B1D**|sew.            86400    IN    DS    **42229** **7** **1 F7F0C3A6110825A925B433213F69B89AF3957504**|
|a0.nic.sew.        **172800**    IN    **A**    **65.22.188.25**|**sew.            86400    IN    DS    42229 7 **2 **7A3DCF7E5C194B9D52A45D55684B72378C9BB397BF24C063FFC37FABB91B7509**|
|a0.nic.sew.        **172800**    IN    **AAAA**    **2a01:8840:b6:0:0:0:0:25**|a0.nic.sew.        **518400**    IN    **AAAA**    **2a01:8840:b6:0:0:0:0:25**|
|a2.nic.sew.        **172800**    IN    A    65.22.191.25|a0.nic.sew.        **518400**    IN    **A**    **65.22.188.25**|
|a2.nic.sew.        **172800**    IN    AAAA    2a01:8840:b9:0:0:0:0:25|a2.nic.sew.        **518400**    IN    A    65.22.191.25|
|b0.nic.sew.        **172800**    IN    A    65.22.189.25|a2.nic.sew.        **518400**    IN    AAAA    2a01:8840:b9:0:0:0:0:25|
|b0.nic.sew.        **172800**    IN    AAAA    2a01:8840:b7:0:0:0:0:25|b0.nic.sew.        **518400**    IN    A    65.22.189.25|
|c0.nic.sew.        **172800**    IN    **A**    **65.22.190.25**|b0.nic.sew.        **518400**    IN    AAAA    2a01:8840:b7:0:0:0:0:25|
|c0.nic.sew.        **172800**    IN    **AAAA**    **2a01:8840:b8:0:0:0:0:25**|c0.nic.sew.        **518400**    IN    **AAAA**    **2a01:8840:b8:0:0:0:0:25**|
||c0.nic.sew.        **518400**    IN    **A**    **65.22.190.25**|
#
## ch
|expected|actual|
|--------|---|
|ch.            86400    IN    DS    **1053** 13 2 **94D834BEF7536BFE6ECB4682E1151BDD4882CA12C6DB2C1AA64CB0E9D4DA5222**|ch.            86400    IN    DS    **55966** 13 2 **CEB479416E4EFD770800434BE1245E1B10D4CF018255C11D8544C448FA032B32**|
|a.nic.ch.        **172800**    IN    A    130.59.31.41|a.nic.ch.        **518400**    IN    A    130.59.31.41|
|a.nic.ch.        **172800**    IN    AAAA    2001:620:0:ff:0:0:0:56|a.nic.ch.        **518400**    IN    AAAA    2001:620:0:ff:0:0:0:56|
|b.nic.ch.        **172800**    IN    A    130.59.31.43|b.nic.ch.        **518400**    IN    A    130.59.31.43|
|b.nic.ch.        **172800**    IN    AAAA    2001:620:0:ff:0:0:0:58|b.nic.ch.        **518400**    IN    AAAA    2001:620:0:ff:0:0:0:58|
|c.nic.ch.        **172800**    IN    A    74.116.178.40|c.nic.ch.        **518400**    IN    A    74.116.178.40|
|c.nic.ch.        **172800**    IN    AAAA    2620:7d:e000:0:0:0:0:28|c.nic.ch.        **518400**    IN    AAAA    2620:7d:e000:0:0:0:0:28|
|e.nic.ch.        **172800**    IN    A    194.0.17.1|e.nic.ch.        **518400**    IN    A    194.0.17.1|
|e.nic.ch.        **172800**    IN    AAAA    2001:678:3:0:0:0:0:1|e.nic.ch.        **518400**    IN    AAAA    2001:678:3:0:0:0:0:1|
|f.nic.ch.        **172800**    IN    **A**    **194.146.106.10**|f.nic.ch.        **518400**    IN    **AAAA**    **2001:67c:1010:2:0:0:0:53**|
|f.nic.ch.        **172800**    IN    **AAAA**    **2001:67c:1010:2:0:0:0:53**|f.nic.ch.        **518400**    IN    **A**    **194.146.106.10**|
|g.nic.ch.        **172800**    IN    A    194.0.1.40|g.nic.ch.        **518400**    IN    A    194.0.1.40|
|g.nic.ch.        **172800**    IN    AAAA    2001:678:4:0:0:0:0:28|g.nic.ch.        **518400**    IN    AAAA    2001:678:4:0:0:0:0:28|
|h.nic.ch.        **172800**    IN    **A**    **85.119.5.230**|h.nic.ch.        **518400**    IN    **AAAA**    **2a03:bd80:36:0:0:1:203:230**|
|h.nic.ch.        **172800**    IN    **AAAA**    **2a03:bd80:36:0:0:1:203:230**|h.nic.ch.        **518400**    IN    **A**    **85.119.5.230**|
#
## jobs
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## co
|expected|actual|
|--------|---|
|**co.            86400    IN    DS    43834 8 1 4957CA93E0D6029AC8BFDF039AD22E98AD721ADB**||
|ns1.cctld.co.        **172800**    IN    A    **37**.**209**.**192**.**14**|**co.            86400    IN    DS    43834 8 1 4957CA93E0D6029AC8BFDF039AD22E98AD721ADB**|
|ns1.cctld.co.        **172800**    IN    AAAA    **2001:dcd:1:0:0:0:0:14**|ns1.cctld.co.        **518400**    IN    A    **156**.**154**.**100**.**25**|
|ns2.cctld.co.        **172800**    IN    **A**    **37.209.194.14**|ns1.cctld.co.        **518400**    IN    AAAA    **2001:502:2eda:0:0:0:0:21**|
|ns2.cctld.co.        **172800**    IN    **AAAA**    **2001:dcd:2:0:0:0:0:14**|ns2.cctld.co.        **518400**    IN    **AAAA**    **2001:502:ad09:0:0:0:0:21**|
|ns3.cctld.co.        **172800**    IN    **A**    **37.209.196.14**|ns2.cctld.co.        **518400**    IN    **A**    **156.154.101.25**|
|ns3.cctld.co.        **172800**    IN    **AAAA**    **2001:dcd:3:0:0:0:0:14**|ns3.cctld.co.        **518400**    IN    **AAAA**    **2610:a1:1009:0:0:0:0:21**|
|ns4.cctld.co.        **172800**    IN    A    156.154.103.25|ns3.cctld.co.        **518400**    IN    **A**    **156.154.102.25**|
|ns4.cctld.co.        **172800**    IN    AAAA    2610:a1:1010:0:0:0:0:21|ns4.cctld.co.        **518400**    IN    A    156.154.103.25|
|ns5.cctld.co.        **172800**    IN    A    156.154.104.25|ns4.cctld.co.        **518400**    IN    AAAA    2610:a1:1010:0:0:0:0:21|
|ns5.cctld.co.        **172800**    IN    AAAA    2610:a1:1011:0:0:0:0:21|ns5.cctld.co.        **518400**    IN    A    156.154.104.25|
|ns6.cctld.co.        **172800**    IN    A    156.154.105.25|ns5.cctld.co.        **518400**    IN    AAAA    2610:a1:1011:0:0:0:0:21|
|ns6.cctld.co.        **172800**    IN    AAAA    2610:a1:1012:0:0:0:0:21|ns6.cctld.co.        **518400**    IN    A    156.154.105.25|
||ns6.cctld.co.        **518400**    IN    AAAA    2610:a1:1012:0:0:0:0:21|
#
## bing
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## food
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## cookingchannel
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## tatamotors
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## cx
|expected|actual|
|--------|---|
|**cx.            172800    IN    NS    ns.cocca.fr.**||
||**cx.            172800    IN    NS    ns.cocca.fr.**|
|ns.anycast.nic.cx.    **172800**    IN    A    204.61.216.16|ns.anycast.nic.cx.    **518400**    IN    **AAAA    2001:500:14:6016:ad:0:0:1**|
|ns.**anycast**.**nic**.**cx.**    **172800**    IN    **AAAA**    **2001:500:14:6016:ad:0:0:1**|**ns.anycast.nic.cx.    518400    IN    **A    204.61.216.16|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.**93**|ns.**cocca**.**fr**.        **518400**    IN    **A**    **185.17.236.93**|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    A    185.17.236.**123**|
||ns.cocca.fr.        **518400**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|
#
## visa
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## beauty
|expected|actual|
|--------|---|
|beauty.            172800    IN    NS    **a**.**nic**.**beauty**.|beauty.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|beauty.            172800    IN    NS    **b**.**nic**.**beauty**.|beauty.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|beauty.            172800    IN    NS    **c**.**nic**.**beauty**.|beauty.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|beauty.            172800    IN    NS    **d**.**nic**.**beauty**.|beauty.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**beauty**.**            86400    IN    DS    52406 8 2 C5C45B79DBE67A132237B020F4966FE32FBE61553487E38D47918561568E9957**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**beauty.**        **172800**    IN    A    **194**.**169**.**218**.**119**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**a**.**nic**.**beauty**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:119**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b.nic.beauty.        172800    IN    **A    **185**.**24**.**64**.**119**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**b**.**nic**.**beauty**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:119**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**beauty**.        **172800**    IN    A    **212**.**18**.**248**.**119**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**c**.**nic**.**beauty**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:119**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**beauty**.        **172800**    IN    **A**    **212.18.249.119**||
|**d**.**nic**.**beauty**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:119**||
#
## xn--nqv7fs00ema
|expected|actual|
|--------|---|
|xn--nqv7fs00ema.    86400    IN    DS    **28897** **8** 2 **6429B014E65CE5BD280E303E77C65ED29B9018FD717157B19871CD63994758F2**|xn--nqv7fs00ema.    86400    IN    DS    **36904** **7** **1 33BFFC69FF25791261FB005397C255D13CF63A65**|
|a0.nic.xn--nqv7fs00ema.    **172800**    IN    **A**    **65.22.184.9**|**xn--nqv7fs00ema.    86400    IN    DS    36904 7 **2 **32E8D5C0322C27C7AAC0E1F1F7DC4E611B8C64EF8DF8E9221EED5E19588944EC**|
|a0.nic.xn--nqv7fs00ema.    **172800**    IN    **AAAA**    **2a01:8840:b2:0:0:0:0:9**|a0.nic.xn--nqv7fs00ema.    **518400**    IN    **AAAA**    **2a01:8840:b2:0:0:0:0:9**|
|a2.nic.xn--nqv7fs00ema.    **172800**    IN    A    65.22.187.9|a0.nic.xn--nqv7fs00ema.    **518400**    IN    **A**    **65.22.184.9**|
|a2.nic.xn--nqv7fs00ema.    **172800**    IN    AAAA    2a01:8840:b5:0:0:0:0:9|a2.nic.xn--nqv7fs00ema.    **518400**    IN    A    65.22.187.9|
|b0.nic.xn--nqv7fs00ema.    **172800**    IN    **A**    **65.22.185.9**|a2.nic.xn--nqv7fs00ema.    **518400**    IN    AAAA    2a01:8840:b5:0:0:0:0:9|
|b0.nic.xn--nqv7fs00ema.    **172800**    IN    **AAAA**    **2a01:8840:b3:0:0:0:0:9**|b0.nic.xn--nqv7fs00ema.    **518400**    IN    **AAAA**    **2a01:8840:b3:0:0:0:0:9**|
|c0.nic.xn--nqv7fs00ema.    **172800**    IN    A    65.22.186.9|b0.nic.xn--nqv7fs00ema.    **518400**    IN    **A**    **65.22.185.9**|
|c0.nic.xn--nqv7fs00ema.    **172800**    IN    AAAA    2a01:8840:b4:0:0:0:0:9|c0.nic.xn--nqv7fs00ema.    **518400**    IN    A    65.22.186.9|
||c0.nic.xn--nqv7fs00ema.    **518400**    IN    AAAA    2a01:8840:b4:0:0:0:0:9|
#
## sener
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bet
|expected|actual|
|--------|---|
|bet.            86400    IN    DS    **34666** **8** 2 **E514F93C9FF69EC196E47CDFA00E39946382363CF2CAC7DF3DF562F35B31A2BC**|bet.            86400    IN    DS    **8103** **7** **1 269EB934169B6CC792B71C03A7BF120D2CA5B38A**|
|a0.nic.bet.        **172800**    IN    A    65.22.36.17|**bet.            86400    IN    DS    8103 7 **2 **C8724F921BE7A62655202BC3A0514BE4C7BD68D91D0DE9921B93B5C9E4024573**|
|a0.nic.bet.        **172800**    IN    AAAA    2a01:8840:26:0:0:0:0:17|a0.nic.bet.        **518400**    IN    A    65.22.36.17|
|a2.nic.bet.        **172800**    IN    A    65.22.39.17|a0.nic.bet.        **518400**    IN    AAAA    2a01:8840:26:0:0:0:0:17|
|a2.nic.bet.        **172800**    IN    AAAA    2a01:8840:29:0:0:0:0:17|a2.nic.bet.        **518400**    IN    A    65.22.39.17|
|b0.nic.bet.        **172800**    IN    **A**    **65.22.37.17**|a2.nic.bet.        **518400**    IN    AAAA    2a01:8840:29:0:0:0:0:17|
|b0.nic.bet.        **172800**    IN    **AAAA**    **2a01:8840:27:0:0:0:0:17**|b0.nic.bet.        **518400**    IN    **AAAA**    **2a01:8840:27:0:0:0:0:17**|
|c0.nic.bet.        **172800**    IN    A    65.22.38.17|b0.nic.bet.        **518400**    IN    **A**    **65.22.37.17**|
|c0.nic.bet.        **172800**    IN    AAAA    2a01:8840:28:0:0:0:0:17|c0.nic.bet.        **518400**    IN    A    65.22.38.17|
||c0.nic.bet.        **518400**    IN    AAAA    2a01:8840:28:0:0:0:0:17|
#
## diy
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## showtime
|expected|actual|
|--------|---|
|showtime.        86400    IN    DS    **18211** **8** 2 **127ADBFE87EA3D320525990C4783DB7EAFB3FC10DE688EB7B593836B6CE02CCA**|showtime.        86400    IN    DS    **33033** **7** **1 37F3CA509F7B293243FB72855EB348CDB396FD42**|
|a0.nic.showtime.    **172800**    IN    A    65.22.68.1|**showtime.        86400    IN    DS    33033 7 **2 **8E68841A9DF682561D42D6509148BBAC6E0839C8BC18793D3198DCB661BB8BA8**|
|a0.nic.showtime.    **172800**    IN    AAAA    2a01:8840:42:0:0:0:0:1|a0.nic.showtime.    **518400**    IN    A    65.22.68.1|
|a2.nic.showtime.    **172800**    IN    A    65.22.71.1|a0.nic.showtime.    **518400**    IN    AAAA    2a01:8840:42:0:0:0:0:1|
|a2.nic.showtime.    **172800**    IN    AAAA    2a01:8840:45:0:0:0:0:1|a2.nic.showtime.    **518400**    IN    A    65.22.71.1|
|b0.nic.showtime.    **172800**    IN    **A**    **65.22.69.1**|a2.nic.showtime.    **518400**    IN    AAAA    2a01:8840:45:0:0:0:0:1|
|b0.nic.showtime.    **172800**    IN    **AAAA**    **2a01:8840:43:0:0:0:0:1**|b0.nic.showtime.    **518400**    IN    **AAAA**    **2a01:8840:43:0:0:0:0:1**|
|c0.nic.showtime.    **172800**    IN    A    65.22.70.1|b0.nic.showtime.    **518400**    IN    **A**    **65.22.69.1**|
|c0.nic.showtime.    **172800**    IN    AAAA    2a01:8840:44:0:0:0:0:1|c0.nic.showtime.    **518400**    IN    A    65.22.70.1|
||c0.nic.showtime.    **518400**    IN    AAAA    2a01:8840:44:0:0:0:0:1|
#
## info
|expected|actual|
|--------|---|
|info.            86400    IN    DS    **5104** **8** 2 **1AF7548A8D3E2950C20303757DF9390C26CFA39E26C8B6A8F6C8B1E72DD8F744**|info.            86400    IN    DS    **8674** **7** **1 197789A2CBABA6FECD0B5AC88C5BC414CE1FC309**|
|a0.info.afilias-nst.info.    **172800**    IN    A    199.254.31.1|**info.            86400    IN    DS    8674 7 **2 **EC9B6082B96B5F87143696F2B483ACC9B2C433DCE0C94E70F1FF5648CA18008B**|
|a0.info.afilias-nst.info.    **172800**    IN    AAAA    2001:500:19:0:0:0:0:1|a0.info.afilias-nst.info.    **518400**    IN    A    199.254.31.1|
|a2.info.afilias-nst.info.    **172800**    IN    A    199.249.113.1|a0.info.afilias-nst.info.    **518400**    IN    AAAA    2001:500:19:0:0:0:0:1|
|a2.info.afilias-nst.info.    **172800**    IN    AAAA    2001:500:41:0:0:0:0:1|a2.info.afilias-nst.info.    **518400**    IN    A    199.249.113.1|
|c0.info.afilias-nst.info.    **172800**    IN    A    199.254.49.1|a2.info.afilias-nst.info.    **518400**    IN    AAAA    2001:500:41:0:0:0:0:1|
|c0.info.afilias-nst.info.    **172800**    IN    AAAA    2001:500:1b:0:0:0:0:1|c0.info.afilias-nst.info.    **518400**    IN    A    199.254.49.1|
|b0.info.afilias-nst.org.    **172800**    IN    A    199.254.48.1|c0.info.afilias-nst.info.    **518400**    IN    AAAA    2001:500:1b:0:0:0:0:1|
|b0.info.afilias-nst.org.    **172800**    IN    AAAA    2001:500:1a:0:0:0:0:1|b0.info.afilias-nst.org.    **518400**    IN    A    199.254.48.1|
|b2.info.afilias-nst.org.    **172800**    IN    **A**    **199.249.121.1**|b0.info.afilias-nst.org.    **518400**    IN    AAAA    2001:500:1a:0:0:0:0:1|
|b2.info.afilias-nst.org.    **172800**    IN    **AAAA**    **2001:500:49:0:0:0:0:1**|b2.info.afilias-nst.org.    **518400**    IN    **AAAA**    **2001:500:49:0:0:0:0:1**|
|d0.info.afilias-nst.org.    **172800**    IN    AAAA    2001:500:1c:0:0:0:0:1|b2.info.afilias-nst.org.    **518400**    IN    **A**    **199.249.121.1**|
|d0.info.afilias-nst.org.    **172800**    IN    A    199.254.50.1|d0.info.afilias-nst.org.    **518400**    IN    AAAA    2001:500:1c:0:0:0:0:1|
||d0.info.afilias-nst.org.    **518400**    IN    A    199.254.50.1|
#
## fido
|expected|actual|
|--------|---|
|fido.            86400    IN    DS    **16402** **8** **2** **F1FDB16B12B96A368D95FCC0F2A37BC54588DC9D0049F066AA21FB095E5EA7D7**|fido.            86400    IN    DS    **29505** **7** **1** **377EFC9FF359D3571A5746B73E17231B48ED7EFC**|
|**a0.nic.**fido.        **172800**    IN    **A**    **65.22.108.41**|fido.            **86400**    IN    **DS**    **29505** **7 2 48FA9263BE8DD1BDBCA4F3AE094EB14C92E1CE7A406767EFEC273EB62798317E**|
|a0.nic.fido.        **172800**    IN    AAAA    2a01:8840:6a:0:0:0:0:41|a0.nic.fido.        **518400**    IN    AAAA    2a01:8840:6a:0:0:0:0:41|
|**a2**.nic.fido.        **172800**    IN    A    65.22.**111**.41|**a0**.nic.fido.        **518400**    IN    A    65.22.**108**.41|
|a2.nic.fido.        **172800**    IN    AAAA    2a01:8840:6d:0:0:0:0:41|a2.nic.fido.        **518400**    IN    AAAA    2a01:8840:6d:0:0:0:0:41|
|b0.nic.fido.        **172800**    IN    A    65.22.109.41|**a2.nic.fido.        518400    IN    A    65.22.111.41**|
|b0.nic.fido.        **172800**    IN    AAAA    2a01:8840:6b:0:0:0:0:41|b0.nic.fido.        **518400**    IN    A    65.22.109.41|
|c0.nic.fido.        **172800**    IN    **A**    **65.22.110.41**|b0.nic.fido.        **518400**    IN    AAAA    2a01:8840:6b:0:0:0:0:41|
|c0.nic.fido.        **172800**    IN    **AAAA**    **2a01:8840:6c:0:0:0:0:41**|c0.nic.fido.        **518400**    IN    **AAAA**    **2a01:8840:6c:0:0:0:0:41**|
||c0.nic.fido.        **518400**    IN    **A**    **65.22.110.41**|
#
## xn--w4rs40l
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## temasek
|expected|actual|
|--------|---|
|**temasek.        86400    IN    DS    35989 8 2 225862860C611D932591E3173CA1FF2A1903716878EE30981AB59E1D179570BB**||
|a0.nic.temasek.        **172800**    IN    A    65.22.140.9|**temasek.        86400    IN    DS    47764 7 1 CE46AE409F2CFEC23D5DF289C7AB203F47429625**|
|a0.nic.temasek.        **172800**    IN    AAAA    2a01:8840:8a:0:0:0:0:9|**temasek.        86400    IN    DS    47764 7 2 633F88E7B11734FC2C44546F7773850A13EE48FD20ABA62ED4FF6CA75FE7653C**|
|a2.nic.temasek.        **172800**    IN    A    65.22.143.9|a0.nic.temasek.        **518400**    IN    A    65.22.140.9|
|a2.nic.temasek.        **172800**    IN    AAAA    2a01:8840:8d:0:0:0:0:9|a0.nic.temasek.        **518400**    IN    AAAA    2a01:8840:8a:0:0:0:0:9|
|b0.nic.temasek.        **172800**    IN    A    65.22.141.9|a2.nic.temasek.        **518400**    IN    A    65.22.143.9|
|b0.nic.temasek.        **172800**    IN    AAAA    2a01:8840:8b:0:0:0:0:9|a2.nic.temasek.        **518400**    IN    AAAA    2a01:8840:8d:0:0:0:0:9|
|c0.nic.temasek.        **172800**    IN    A    65.22.142.9|b0.nic.temasek.        **518400**    IN    A    65.22.141.9|
|c0.nic.temasek.        **172800**    IN    AAAA    2a01:8840:8c:0:0:0:0:9|b0.nic.temasek.        **518400**    IN    AAAA    2a01:8840:8b:0:0:0:0:9|
||c0.nic.temasek.        **518400**    IN    A    65.22.142.9|
||c0.nic.temasek.        **518400**    IN    AAAA    2a01:8840:8c:0:0:0:0:9|
#
## fr
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|e.ext.nic.fr.        **172800**    IN    A    193.176.144.22|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|e.ext.nic.fr.        **172800**    IN    AAAA    2a00:d78:0:102:193:176:144:22|e.ext.nic.fr.        **518400**    IN    A    193.176.144.22|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|e.ext.nic.fr.        **518400**    IN    AAAA    2a00:d78:0:102:193:176:144:22|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## schaeffler
|expected|actual|
|--------|---|
|schaeffler.        **86400**    IN    **DS**    **16600** **7 2 FC2D4560A329B6B212D0134F3345FB1A3B59D28D016E1B196CFA967624053C34**|**a0.nic.**schaeffler.    **518400**    IN    **AAAA**    **2a01:8840:ee:0:0:0:0:17**|
|a0.nic.schaeffler.    **172800**    IN    A    65.22.244.17|a0.nic.schaeffler.    **518400**    IN    A    65.22.244.17|
|**a0**.nic.schaeffler.    **172800**    IN    AAAA    **2a01:8840:ee:0:0:0:0:17**|**a2**.nic.schaeffler.    **518400**    IN    AAAA    **2a01:8840:f1:0:0:0:0:17**|
|a2.nic.schaeffler.    **172800**    IN    A    65.22.247.17|a2.nic.schaeffler.    **518400**    IN    A    65.22.247.17|
|**a2.nic.schaeffler.    172800    IN    AAAA    2a01:8840:f1:0:0:0:0:17**|b0.nic.schaeffler.    **518400**    IN    A    65.22.245.17|
|b0.nic.schaeffler.    **172800**    IN    A    65.22.245.17|b0.nic.schaeffler.    **518400**    IN    AAAA    2a01:8840:ef:0:0:0:0:17|
|b0.nic.schaeffler.    **172800**    IN    AAAA    2a01:8840:ef:0:0:0:0:17|c0.nic.schaeffler.    **518400**    IN    **AAAA**    **2a01:8840:f0:0:0:0:0:17**|
|c0.nic.schaeffler.    **172800**    IN    **A**    **65.22.246.17**|c0.nic.schaeffler.    **518400**    IN    **A**    **65.22.246.17**|
|c0.nic.schaeffler.    **172800**    IN    **AAAA**    **2a01:8840:f0:0:0:0:0:17**||
#
## xn--hxt814e
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## xn--5tzm5g
|expected|actual|
|--------|---|
|xn--5tzm5g.        86400    IN    DS    **26359** **8** **2** **7D1E023BBB026AC5D19AE62D5F13EE6E01F3450A1E6629E25A9205DCF2A31F9E**|xn--5tzm5g.        86400    IN    DS    **13249** **7** **1** **800B951D452C29B9A21DFCF6535513D3CECBDBF2**|
|**a0.nic.**xn--5tzm5g.    **172800**    IN    **A**    **65.22.16.9**|xn--5tzm5g.        **86400**    IN    **DS**    **13249** **7 2 F9C57D9B6594B8A8AA132FCC2E4D60F857A8DAFD591FB3B9ABEB312160DBF503**|
|a0.nic.xn--5tzm5g.    **172800**    IN    AAAA    2a01:8840:12:0:0:0:0:9|a0.nic.xn--5tzm5g.    **518400**    IN    AAAA    2a01:8840:12:0:0:0:0:9|
|**a2**.nic.xn--5tzm5g.    **172800**    IN    A    65.22.**19**.9|**a0**.nic.xn--5tzm5g.    **518400**    IN    A    65.22.**16**.9|
|a2.nic.xn--5tzm5g.    **172800**    IN    AAAA    2a01:8840:15:0:0:0:0:9|a2.nic.xn--5tzm5g.    **518400**    IN    AAAA    2a01:8840:15:0:0:0:0:9|
|**b0**.nic.xn--5tzm5g.    **172800**    IN    A    65.22.**17**.9|**a2**.nic.xn--5tzm5g.    **518400**    IN    A    65.22.**19**.9|
|b0.nic.xn--5tzm5g.    **172800**    IN    AAAA    2a01:8840:13:0:0:0:0:9|b0.nic.xn--5tzm5g.    **518400**    IN    AAAA    2a01:8840:13:0:0:0:0:9|
|c0.nic.xn--5tzm5g.    **172800**    IN    A    65.22.18.9|**b0.nic.xn--5tzm5g.    518400    IN    A    65.22.17.9**|
|c0.nic.xn--5tzm5g.    **172800**    IN    AAAA    2a01:8840:14:0:0:0:0:9|c0.nic.xn--5tzm5g.    **518400**    IN    A    65.22.18.9|
||c0.nic.xn--5tzm5g.    **518400**    IN    AAAA    2a01:8840:14:0:0:0:0:9|
#
## mckinsey
|expected|actual|
|--------|---|
|mckinsey.        86400    IN    DS    **27100** **8** **2** **B9D92B7DBF31D3BD3AA6752BD38C50F6B637509E22C438A34677C843B9AFD238**|mckinsey.        86400    IN    DS    **21081** **7** **1** **1C77DD23709AD50C0AD2BA7AA8DD70CB6A06CFDB**|
|**a0.nic.**mckinsey.    **172800**    IN    **A**    **65.22.236.25**|mckinsey.        **86400**    IN    **DS**    **21081** **7 2 E683F1C2C4249E0EE733ECB0C5CEBE220C1FAC450987B726AB6A304099BB17F1**|
|a0.nic.mckinsey.    **172800**    IN    AAAA    2a01:8840:e6:0:0:0:0:25|a0.nic.mckinsey.    **518400**    IN    AAAA    2a01:8840:e6:0:0:0:0:25|
|**a2**.nic.mckinsey.    **172800**    IN    A    65.22.**239**.25|**a0**.nic.mckinsey.    **518400**    IN    A    65.22.**236**.25|
|a2.nic.mckinsey.    **172800**    IN    AAAA    2a01:8840:e9:0:0:0:0:25|a2.nic.mckinsey.    **518400**    IN    AAAA    2a01:8840:e9:0:0:0:0:25|
|**b0**.nic.mckinsey.    **172800**    IN    A    65.22.**237**.25|**a2**.nic.mckinsey.    **518400**    IN    A    65.22.**239**.25|
|b0.nic.mckinsey.    **172800**    IN    AAAA    2a01:8840:e7:0:0:0:0:25|b0.nic.mckinsey.    **518400**    IN    AAAA    2a01:8840:e7:0:0:0:0:25|
|**c0**.nic.mckinsey.    **172800**    IN    A    65.22.**238**.25|**b0**.nic.mckinsey.    **518400**    IN    A    65.22.**237**.25|
|c0.nic.mckinsey.    **172800**    IN    AAAA    2a01:8840:e8:0:0:0:0:25|c0.nic.mckinsey.    **518400**    IN    AAAA    2a01:8840:e8:0:0:0:0:25|
||**c0.nic.mckinsey.    518400    IN    A    65.22.238.25**|
#
## gg
|expected|actual|
|--------|---|
|**gg.            172800    IN    NS    e.ci-servers.net.**||
|gg.            172800    IN    NS    **dns2**.**nominetdns**.**uk**.|gg.            172800    IN    NS    **e**.**ci-servers**.**gg**.|
|gg.            172800    IN    NS    **dns3**.**nominetdns**.**uk**.|gg.            172800    IN    NS    **f**.**ci-servers**.**je**.|
|gg.            172800    IN    NS    **dns4**.**nominetdns**.**uk**.|gg.            172800    IN    NS    **ns0**.**ja**.**net**.|
|gg.            **86400**    IN    **DS**    **4975** **8 2 6B95DA44B57BF3BDFCE8E9CF6D28DF4B0FF999A374EFF7909E095AB1C7000630**|**e.ci-servers.**gg.    **518400**    IN    **AAAA**    **2001:500:14:6074:ad:0:0:1**|
|e.ci-servers.**net**.    **172800**    IN    A    204.61.216.74|e.ci-servers.**gg**.    **518400**    IN    A    204.61.216.74|
|**e**.ci-servers.**net**.    **172800**    IN    **AAAA**    **2001:500:14:6074:ad:0:0:1**|**f**.ci-servers.**je**.    **518400**    IN    **A**    **213**.**248**.**223**.**254**|
|**ns99**.**dns**.**net**.**nz**.    **172800**    IN    **A**    **202.46.190.131**|**f**.**ci-servers.je.**    **518400**    IN    **AAAA**    **2a01:618:407:0:0:0:0:254**|
|**ns99**.**dns**.net.**nz.**    **172800**    IN    **AAAA**    **2001:dce:2000:2:0:0:0:131**|**ns0**.**ja**.net.        **518400**    IN    **A**    **193.63.94.20**|
|**c**.**ci-servers**.**org**.    **172800**    IN    A    **194**.**146**.**106**.**86**|**ns0**.**ja**.**net**.        **518400**    IN    A    **128**.**86**.**1**.**20**|
|**c**.**ci-servers**.**org**.    **172800**    IN    AAAA    **2001:67c:1010:22:0:0:0:53**|**ns0**.**ja**.**net**.        **518400**    IN    AAAA    **2001:630:0:8:0:0:0:14**|
|**dns1**.**nominetdns**.**uk**.    **172800**    IN    **A**    **213.248.219.254**|**ns0**.**ja**.**net**.        **518400**    IN    **AAAA**    **2001:630:0:9:0:0:0:14**|
|**dns1**.**nominetdns**.**uk**.    **172800**    IN    AAAA    **2a01:618:403:0:0:0:0:254**|**ns99**.**dns**.**net**.**nz.**    **518400**    IN    AAAA    **2001:dce:2000:2:0:0:0:131**|
|**dns2**.**nominetdns**.**uk**.    **172800**    IN    A    **103**.**49**.**83**.**254**|**ns99**.**dns**.**net**.**nz.**    **518400**    IN    A    **202**.**46**.**190**.**131**|
|**dns2**.**nominetdns**.**uk**.    **172800**    IN    AAAA    **2401:fd80:403:0:0:0:0:254**|**c**.**ci-servers**.**org**.    **518400**    IN    AAAA    **2001:67c:1010:22:0:0:0:53**|
|**dns3**.**nominetdns**.**uk**.    **172800**    IN    A    **213**.**248**.**223**.**254**|**c**.**ci-servers**.**org**.    **518400**    IN    A    **194**.**146**.**106**.**86**|
|**dns3**.nominetdns.uk.    **172800**    IN    AAAA    **2a01:618:407:0:0:0:0:254**|**dns1**.nominetdns.uk.    **518400**    IN    AAAA    **2a01:618:403:0:0:0:0:254**|
|**dns4**.nominetdns.uk.    **172800**    IN    A    **43**.**230**.**51**.254|**dns1**.nominetdns.uk.    **518400**    IN    A    **213**.**248**.**219**.254|
|**dns4.nominetdns.uk.    172800    IN    AAAA    2401:fd80:407:0:0:0:0:254**||
#
## gi
|expected|actual|
|--------|---|
|gi.            86400    IN    DS    **33934** **8** 2 **3DB5809DE2E1052B00E010F54B404BD59CB5CBA0C8306E1799623BDA45A1CFB7**|gi.            86400    IN    DS    **40935** **7** **1 A6110BBAB0C51F4712CF1DF57F960CC73C7645F6**|
|a0.cctld.afilias-nst.info.    **172800**    IN    A    199.254.59.1|**gi.            86400    IN    DS    40935 7 **2 **9F19CCCE0100976D6A4ED5D0AFA3D66E88C6974722D62EE6251F9D3DFA74A23F**|
|a0.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:1|a0.cctld.afilias-nst.info.    **518400**    IN    A    199.254.59.1|
|a2.cctld.afilias-nst.info.    **172800**    IN    A    199.249.116.1|a0.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:1|
|a2.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:1|a2.cctld.afilias-nst.info.    **518400**    IN    A    199.249.116.1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **A**    **199.254.61.1**|a2.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|c0.cctld.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.60.1|c0.cctld.afilias-nst.info.    **518400**    IN    **A**    **199.254.61.1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:26:0:0:0:0:1|b0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.60.1|
|b2.cctld.afilias-nst.org.    **172800**    IN    A    199.249.124.1|b0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:26:0:0:0:0:1|
|b2.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4c:0:0:0:0:1|b2.cctld.afilias-nst.org.    **518400**    IN    A    199.249.124.1|
|d0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.62.1|b2.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4c:0:0:0:0:1|
|d0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:1|d0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.62.1|
||d0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:1|
#
## living
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## gl
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|d.nic.gl.        **172800**    IN    **A**    **204.61.216.49**|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|d.nic.gl.        **172800**    IN    **AAAA**    **2001:500:14:6049:ad:0:0:1**|d.nic.gl.        **518400**    IN    **AAAA**    **2001:500:14:6049:ad:0:0:1**|
|a.nuuk.nic.gl.        **172800**    IN    A    194.177.224.13|d.nic.gl.        **518400**    IN    **A**    **204.61.216.49**|
||a.nuuk.nic.gl.        **518400**    IN    A    194.177.224.13|
#
## asia
|expected|actual|
|--------|---|
|asia.            86400    IN    DS    **23407** **8** 2 **0F51A4E5EF96B66C2078F7735B41860C83DA0746DDDA1A1B2B893AB056B3058C**|asia.            86400    IN    DS    **13890** **7** **1 A33A41F9B31E945CB3379FC36663887038927577**|
|b0.asia.afilias-nst.asia.    **172800**    IN    A    199.254.28.1|**asia.            86400    IN    DS    13890 7 **2 **F7F1B03479CE200A0680158258D1B7925B0A5F273E54E6BDE742D13214DD99CB**|
|b0.asia.afilias-nst.asia.    **172800**    IN    AAAA    2001:500:16:0:0:0:0:1|b0.asia.afilias-nst.asia.    **518400**    IN    A    199.254.28.1|
|d0.asia.afilias-nst.asia.    **172800**    IN    A    199.254.30.1|b0.asia.afilias-nst.asia.    **518400**    IN    AAAA    2001:500:16:0:0:0:0:1|
|**d0**.asia.afilias-nst.**asia**.    **172800**    IN    AAAA    **2001:500:18:0:0:0:0:1**|d0.asia.afilias-nst.asia.    **518400**    IN    **AAAA    2001:500:18:0:0:0:0:1**|
|a0.asia.afilias-nst.info.    **172800**    IN    A    199.19.55.1|**d0.asia.afilias-nst.asia.    518400    IN    **A    199.254.30.1|
|**a0**.asia.afilias-nst.info.    **172800**    IN    AAAA    **2001:500:d:0:0:0:0:1**|**a0**.asia.afilias-nst.**info**.    **518400**    IN    AAAA    **2001:500:d:0:0:0:0:1**|
|a2.asia.afilias-nst.info.    **172800**    IN    A    199.249.114.1|a0.asia.afilias-nst.info.    **518400**    IN    A    199.19.55.1|
|**a2.asia.afilias-nst.info.    172800    IN    AAAA    2001:500:42:0:0:0:0:1**|**a2**.asia.afilias-nst.info.    **518400**    IN    AAAA    **2001:500:42:0:0:0:0:1**|
|c0.asia.afilias-nst.info.    **172800**    IN    A    199.254.29.1|a2.asia.afilias-nst.info.    **518400**    IN    A    199.249.114.1|
|c0.asia.afilias-nst.info.    **172800**    IN    AAAA    2001:500:17:0:0:0:0:1|c0.asia.afilias-nst.info.    **518400**    IN    A    199.254.29.1|
|b2.asia.afilias-nst.org.    **172800**    IN    **A**    **199.249.122.1**|c0.asia.afilias-nst.info.    **518400**    IN    AAAA    2001:500:17:0:0:0:0:1|
|b2.asia.afilias-nst.org.    **172800**    IN    **AAAA**    **2001:500:4a:0:0:0:0:1**|b2.asia.afilias-nst.org.    **518400**    IN    **AAAA**    **2001:500:4a:0:0:0:0:1**|
||b2.asia.afilias-nst.org.    **518400**    IN    **A**    **199.249.122.1**|
#
## goodyear
|expected|actual|
|--------|---|
|goodyear.        86400    IN    DS    **43276** **8** 2 **31677E86241AF9FAC9000AE3681F1054BB94FADE26D91A92109547D4231A64BC**|goodyear.        86400    IN    DS    **16000** **7** **1 C1EC045E3D0F7804C2CED408518E6A036E8D02B6**|
|a0.nic.goodyear.    **172800**    IN    **A**    **65.22.120.41**|**goodyear.        86400    IN    DS    16000 7 **2 **E1E311EF8A614D2AFA79B5128AC62FCE8CE83251359A566EEB90F370662AA8CD**|
|a0.nic.goodyear.    **172800**    IN    **AAAA**    **2a01:8840:76:0:0:0:0:41**|a0.nic.goodyear.    **518400**    IN    **AAAA**    **2a01:8840:76:0:0:0:0:41**|
|a2.nic.goodyear.    **172800**    IN    A    65.22.123.41|a0.nic.goodyear.    **518400**    IN    **A**    **65.22.120.41**|
|a2.nic.goodyear.    **172800**    IN    AAAA    2a01:8840:79:0:0:0:0:41|a2.nic.goodyear.    **518400**    IN    A    65.22.123.41|
|b0.nic.goodyear.    **172800**    IN    **A**    **65.22.121.41**|a2.nic.goodyear.    **518400**    IN    AAAA    2a01:8840:79:0:0:0:0:41|
|b0.nic.goodyear.    **172800**    IN    **AAAA**    **2a01:8840:77:0:0:0:0:41**|b0.nic.goodyear.    **518400**    IN    **AAAA**    **2a01:8840:77:0:0:0:0:41**|
|c0.nic.goodyear.    **172800**    IN    A    65.22.122.41|b0.nic.goodyear.    **518400**    IN    **A**    **65.22.121.41**|
|c0.nic.goodyear.    **172800**    IN    AAAA    2a01:8840:78:0:0:0:0:41|c0.nic.goodyear.    **518400**    IN    A    65.22.122.41|
||c0.nic.goodyear.    **518400**    IN    AAAA    2a01:8840:78:0:0:0:0:41|
#
## gs
|expected|actual|
|--------|---|
|**gs.            172800    IN    NS    ns.cocca.fr.**||
||**gs.            172800    IN    NS    ns.cocca.fr.**|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|ns.anycast.nic.gs.    **172800**    IN    A    204.61.216.21|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|ns.anycast.nic.gs.    **172800**    IN    AAAA    2001:500:14:6021:ad:0:0:1|ns.anycast.nic.gs.    **518400**    IN    A    204.61.216.21|
||ns.anycast.nic.gs.    **518400**    IN    AAAA    2001:500:14:6021:ad:0:0:1|
#
## gy
|expected|actual|
|--------|---|
|**gy.            172800    IN    NS    ns.cocca.fr.**||
||**gy.            172800    IN    NS    ns.cocca.fr.**|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|gy-ns.anycast.pch.net.    **172800**    IN    A    204.61.216.34|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|gy-ns.anycast.pch.net.    **172800**    IN    AAAA    2001:500:14:6034:ad:0:0:1|gy-ns.anycast.pch.net.    **518400**    IN    A    204.61.216.34|
|a.lactld.org.        **172800**    IN    **A**    **200.0.68.10**|gy-ns.anycast.pch.net.    **518400**    IN    AAAA    2001:500:14:6034:ad:0:0:1|
|a.lactld.org.        **172800**    IN    **AAAA**    **2801:14:a000:0:0:0:0:10**|a.lactld.org.        **518400**    IN    **AAAA**    **2801:14:a000:0:0:0:0:10**|
||a.lactld.org.        **518400**    IN    **A**    **200.0.68.10**|
#
## obi
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--tckwe
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## hk
|expected|actual|
|--------|---|
|hk.            86400    IN    DS    **38227** 8 **1** **1FBA2DEEC4911051D5192E5E1C29D068B056FDF3**|hk.            86400    IN    DS    **36746** 8 **2** **2AA25EDBEA1519DE7E1E264165BBC72627868F1A2B19DC7DE5417ADD9B56E02E**|
|hk.            86400    IN    DS    **38227** 8 **2** **80561534799648DF777A3B0F7AACDB518170404F355007FE8B118A4998A50DA6**|hk.            86400    IN    DS    **36746** 8 **1** **3F84E13235BA03D337B1D95D1F2A9549DBD91636**|
|c.hkirc.net.hk.        **172800**    IN    A    203.119.2.218|c.hkirc.net.hk.        **518400**    IN    **AAAA    2001:dca:4000:0:0:0:cb77:2da**|
|**c**.hkirc.net.hk.        **172800**    IN    AAAA    **2001:dca:4000:0:0:0:cb77:2da**|**c.hkirc.net.hk.        518400    IN    **A    203.119.2.218|
|d.hkirc.net.hk.        **172800**    IN    A    203.119.87.218|**d**.hkirc.net.hk.        **518400**    IN    AAAA    **2001:dca:2000:0:0:0:cb77:57da**|
|**d**.hkirc.net.hk.        **172800**    IN    AAAA    **2001:dca:2000:0:0:0:cb77:57da**|d.hkirc.net.hk.        **518400**    IN    A    203.119.87.218|
|t.hkirc.net.hk.        **172800**    IN    A    202.12.31.53|**t**.hkirc.net.hk.        **518400**    IN    AAAA    **2001:dd8:12:0:0:0:0:53**|
|**t**.hkirc.net.hk.        **172800**    IN    AAAA    **2001:dd8:12:0:0:0:0:53**|t.hkirc.net.hk.        **518400**    IN    A    202.12.31.53|
|u.hkirc.net.hk.        **172800**    IN    A    210.201.138.58|**u**.hkirc.net.hk.        **518400**    IN    AAAA    **2404:0:10a0:0:0:0:0:58**|
|**u**.hkirc.net.hk.        **172800**    IN    AAAA    **2404:0:10a0:0:0:0:0:58**|u.hkirc.net.hk.        **518400**    IN    A    210.201.138.58|
|v.hkirc.net.hk.        **172800**    IN    A    204.61.216.46|**v**.hkirc.net.hk.        **518400**    IN    AAAA    **2001:500:14:6046:ad:0:0:1**|
|**v.hkirc.net.hk.        172800    IN    AAAA    2001:500:14:6046:ad:0:0:1**|v.hkirc.net.hk.        **518400**    IN    A    204.61.216.46|
|x.hkirc.net.hk.        **172800**    IN    A    202.45.188.39|x.hkirc.net.hk.        **518400**    IN    A    202.45.188.39|
|x.hkirc.net.hk.        **172800**    IN    AAAA    2405:3001:1:3a:0:0:0:27|x.hkirc.net.hk.        **518400**    IN    AAAA    2405:3001:1:3a:0:0:0:27|
|y.hkirc.net.hk.        **172800**    IN    A    137.189.6.21|y.hkirc.net.hk.        **518400**    IN    A    137.189.6.21|
|y.hkirc.net.hk.        **172800**    IN    AAAA    2405:3000:3:6:0:0:0:15|y.hkirc.net.hk.        **518400**    IN    AAAA    2405:3000:3:6:0:0:0:15|
|z.hkirc.net.hk.        **172800**    IN    A    194.146.106.70|z.hkirc.net.hk.        **518400**    IN    A    194.146.106.70|
|z.hkirc.net.hk.        **172800**    IN    AAAA    2001:67c:1010:17:0:0:0:53|z.hkirc.net.hk.        **518400**    IN    AAAA    2001:67c:1010:17:0:0:0:53|
#
## bio
|expected|actual|
|--------|---|
|bio.            172800    IN    NS    a0.nic.**bio**.|bio.            172800    IN    NS    a0.nic.**abbott**.|
|bio.            172800    IN    NS    a2.nic.**bio**.|bio.            172800    IN    NS    a2.nic.**abbott**.|
|bio.            **172800    IN    NS    b0.nic.bio.**|bio.            86400    IN    DS    **62559** 8 2 **2DD7BF24AC488D85BC3F9D3F817D37DE9F608E79403FA29E26A55679254F6F28**|
|**bio.            172800    IN    NS    c0.nic.bio.**|a0.nic.**abbott**.        **518400**    IN    A    65.22.**156**.**41**|
|**bio.            **86400    IN    DS    **16334** 8 2 **AEAF99CE9C6F64B1607605DAE987D3BD0ACD4C5490691322B98C592C9C27B14B**|a0.nic.**abbott**.        **518400**    IN    AAAA    **2a01:8840:9a:0:0:0:0:41**|
|a0.nic.**bio**.        **172800**    IN    A    65.22.**84**.**9**|a2.nic.**abbott**.        **518400**    IN    A    65.22.**159**.**41**|
|a0.nic.**bio**.        **172800**    IN    AAAA    **2a01:8840:52:0:0:0:0:9**|a2.nic.**abbott**.        **518400**    IN    AAAA    **2a01:8840:9d:0:0:0:0:41**|
|a2.nic.**bio**.        **172800**    IN    A    65.22.**87**.**9**||
|a2.nic.**bio**.        **172800**    IN    AAAA    **2a01:8840:55:0:0:0:0:9**||
|**b0.nic.bio.        172800    IN    A    65.22.85.9**||
|**b0.nic.bio.        172800    IN    AAAA    2a01:8840:53:0:0:0:0:9**||
|**c0.nic.bio.        172800    IN    A    65.22.86.9**||
|**c0.nic.bio.        172800    IN    AAAA    2a01:8840:54:0:0:0:0:9**||
#
## hr
|expected|actual|
|--------|---|
|**hr.            172800    IN    NS    n.dns.hr.**||
|**hr.            172800    IN    NS    pch.carnet.hr.**||
||**hr.            172800    IN    NS    pch.carnet.hr.**|
|hr-ns-1.carnet.hr.    **172800**    IN    **A**    **161.53.160.100**|hr-ns-1.carnet.hr.    **518400**    IN    **AAAA**    **2001:b68:ff:1:0:0:0:100**|
|hr-ns-1.carnet.hr.    **172800**    IN    **AAAA    2001:b68:ff:1:0:0:0:100**|hr-ns-1.carnet.hr.    **518400**    IN    A    **161**.**53**.**160**.**100**|
|**pch.carnet.hr.        172800    IN    **A    **204**.**61**.**216**.**90**|pch.carnet.hr.        **518400**    IN    AAAA    2001:500:14:6090:ad:0:0:1|
|pch.carnet.hr.        **172800**    IN    AAAA    2001:500:14:6090:ad:0:0:1|**pch**.**carnet**.hr.        **518400**    IN    A    **204**.**61**.**216**.**90**|
|**n**.**dns**.hr.        **172800**    IN    A    **194**.**146**.**106**.**142**||
|**n.dns.hr.        172800    IN    AAAA    2001:67c:1010:36:0:0:0:53**||
#
## ht
|expected|actual|
|--------|---|
||**ht.            172800    IN    NS    charles.cdec.polymtl.ca.**|
||**ht.            172800    IN    NS    ht-ns.anycast.pch.net.**|
|**ht.            172800    IN    NS    ns1.polymtl.ca.**||
|**ht**.            **172800**    IN    **NS**    **pch**.**nic**.**ht**.|**charles**.**cdec.polymtl.ca.**    **518400**    IN    **A**    **132**.**207**.**144**.**2**|
|**ns1**.**polymtl**.**ca**.        **172800**    IN    A    **132**.**207**.**6**.**11**|**ns**.**cocca**.**fr**.        **518400**    IN    A    **185**.**17**.**236**.**93**|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.**93**|ns.cocca.fr.        **518400**    IN    A    185.17.236.**123**|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|
|ns3.nic.fr.        **172800**    IN    A    192.134.0.49|ns3.nic.fr.        **518400**    IN    A    192.134.0.49|
|ns3.nic.fr.        **172800**    IN    AAAA    2001:660:3006:1:0:0:1:1|ns3.nic.fr.        **518400**    IN    AAAA    2001:660:3006:1:0:0:1:1|
|ns1.nic.ht.        **172800**    IN    A    200.115.182.11|ns1.nic.ht.        **518400**    IN    A    200.115.182.11|
|**pch**.**nic**.**ht**.        **172800**    IN    **A**    **204**.**61**.**216.38**|**ht-ns**.**anycast**.**pch**.**net.**    **518400**    IN    **AAAA**    **2001:500:14:6038:ad:0:0:1**|
|pch.**nic**.**ht.**        **172800**    IN    **AAAA**    **2001:500:14:6038:ad:0:0:1**|**ht-ns**.**anycast**.pch.**net**.    **518400**    IN    **A**    **204.61.216.38**|
#
## ski
|expected|actual|
|--------|---|
||**ski.            86400    IN    DS    62489 8 1 512D8B1CB41109FD9D142CA2E733D109F9C08CD3**|
|a0.nic.ski.        **172800**    IN    A    65.22.84.17|a0.nic.ski.        **518400**    IN    A    65.22.84.17|
|a0.nic.ski.        **172800**    IN    AAAA    2a01:8840:52:0:0:0:0:17|a0.nic.ski.        **518400**    IN    AAAA    2a01:8840:52:0:0:0:0:17|
|a2.nic.ski.        **172800**    IN    A    65.22.87.17|a2.nic.ski.        **518400**    IN    **AAAA    2a01:8840:55:0:0:0:0:17**|
|**a2**.nic.ski.        **172800**    IN    AAAA    **2a01:8840:55:0:0:0:0:17**|**a2.nic.ski.        518400    IN    **A    65.22.87.17|
|b0.nic.ski.        **172800**    IN    A    65.22.85.17|**b0**.nic.ski.        **518400**    IN    AAAA    **2a01:8840:53:0:0:0:0:17**|
|**b0**.nic.ski.        **172800**    IN    AAAA    **2a01:8840:53:0:0:0:0:17**|b0.nic.ski.        **518400**    IN    A    65.22.85.17|
|c0.nic.ski.        **172800**    IN    A    65.22.86.17|**c0**.nic.ski.        **518400**    IN    AAAA    **2a01:8840:54:0:0:0:0:17**|
|**c0.nic.ski.        172800    IN    AAAA    2a01:8840:54:0:0:0:0:17**|c0.nic.ski.        **518400**    IN    A    65.22.86.17|
#
## ie
|expected|actual|
|--------|---|
|**ie.            86400    IN    DS    15040 13 2 966EC13E38AD71EB585FB1982308930D96CF88873A065188AC11C469435ABD39**||
|b.ns.ie.        **172800**    IN    A    77.72.72.34|b.ns.ie.        **518400**    IN    A    77.72.72.34|
|b.ns.ie.        **172800**    IN    AAAA    2a01:4b0:0:0:0:0:0:2|b.ns.ie.        **518400**    IN    AAAA    2a01:4b0:0:0:0:0:0:2|
|c.ns.ie.        **172800**    IN    **A**    **194.146.106.98**|c.ns.ie.        **518400**    IN    **AAAA**    **2001:67c:1010:25:0:0:0:53**|
|c.ns.ie.        **172800**    IN    **AAAA**    **2001:67c:1010:25:0:0:0:53**|c.ns.ie.        **518400**    IN    **A**    **194.146.106.98**|
|d.ns.ie.        **172800**    IN    A    77.72.229.245|d.ns.ie.        **518400**    IN    A    77.72.229.245|
|d.ns.ie.        **172800**    IN    AAAA    2a01:3f0:0:309:0:0:0:53|d.ns.ie.        **518400**    IN    AAAA    2a01:3f0:0:309:0:0:0:53|
|g.ns.ie.        **172800**    IN    A    192.111.39.100|g.ns.ie.        **518400**    IN    A    192.111.39.100|
|g.ns.ie.        **172800**    IN    AAAA    2001:7c8:2:a:0:0:0:64|g.ns.ie.        **518400**    IN    AAAA    2001:7c8:2:a:0:0:0:64|
|h.ns.ie.        **172800**    IN    A    192.93.0.4|h.ns.ie.        **518400**    IN    **AAAA    2001:660:3005:1:0:0:1:2**|
|**h**.ns.ie.        **172800**    IN    AAAA    **2001:660:3005:1:0:0:1:2**|**h.ns.ie.        518400    IN    **A    192.93.0.4|
|i.ns.ie.        **172800**    IN    A    194.0.25.35|**i**.ns.ie.        **518400**    IN    AAAA    **2001:678:20:0:0:0:0:35**|
|**i.ns.ie.        172800    IN    AAAA    2001:678:20:0:0:0:0:35**|i.ns.ie.        **518400**    IN    A    194.0.25.35|
#
## abarth
|expected|actual|
|--------|---|
|abarth.            86400    IN    DS    **62281** **8** **2** **8BE9E8B680BC10289EA71A8B7C34FE0CDBAA86242B2C38541DE454526DF041A4**|abarth.            86400    IN    DS    **3648** **7** **1** **BBE522E3F7151A144522BF4E5BFC2D4E503727E3**|
|**a0.nic.**abarth.        **172800**    IN    **A**    **65.22.24.17**|abarth.            **86400**    IN    **DS**    **3648** **7 2 AC305C0759443E2E43A06FC9AF1004EA466D21879B19FBBC35F6D752F792FA35**|
|a0.nic.abarth.        **172800**    IN    AAAA    2a01:8840:1a:0:0:0:0:17|a0.nic.abarth.        **518400**    IN    AAAA    2a01:8840:1a:0:0:0:0:17|
|**a2**.nic.abarth.        **172800**    IN    A    65.22.**27**.17|**a0**.nic.abarth.        **518400**    IN    A    65.22.**24**.17|
|a2.nic.abarth.        **172800**    IN    AAAA    2a01:8840:1d:0:0:0:0:17|a2.nic.abarth.        **518400**    IN    AAAA    2a01:8840:1d:0:0:0:0:17|
|**b0**.nic.abarth.        **172800**    IN    A    65.22.**25**.17|**a2**.nic.abarth.        **518400**    IN    A    65.22.**27**.17|
|b0.nic.abarth.        **172800**    IN    AAAA    2a01:8840:1b:0:0:0:0:17|b0.nic.abarth.        **518400**    IN    AAAA    2a01:8840:1b:0:0:0:0:17|
|**c0**.nic.abarth.        **172800**    IN    A    65.22.**26**.17|**b0**.nic.abarth.        **518400**    IN    A    65.22.**25**.17|
|c0.nic.abarth.        **172800**    IN    AAAA    2a01:8840:1c:0:0:0:0:17|c0.nic.abarth.        **518400**    IN    AAAA    2a01:8840:1c:0:0:0:0:17|
||**c0.nic.abarth.        518400    IN    A    65.22.26.17**|
#
## crown
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sky
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## il
|expected|actual|
|--------|---|
||**il.            172800    IN    NS    ilns.ilan.net.il.**|
||**il.            172800    IN    NS    lookup.iucc.ac.il.**|
|il.            **172800    IN    NS    ilns.ilan.net.il.**|il.            86400    IN    DS    **38495** 8 2 **CD89F213712829A920CC89C9D20EC89C3EAFF922D4DD03B76C7923AA7C43FB08**|
|**il.            172800    IN    NS    lookup.iucc.ac.il.**|lookup.iucc.ac.il.    **518400**    IN    A    128.139.34.240|
|**il.            **86400    IN    DS    **64444** 8 2 **CDF58D5DAF76787214A8ECAF5337A7EAB713EFAB5518B99B1595688BBDAB2F74**|lookup.iucc.ac.il.    **518400**    IN    AAAA    2001:bf8:900:6:0:0:808b:22f0|
|lookup.iucc.ac.il.    **172800**    IN    A    128.139.34.240|ilns.ilan.net.il.    **518400**    IN    A    128.139.35.5|
|lookup.iucc.ac.il.    **172800**    IN    AAAA    2001:bf8:900:6:0:0:808b:22f0|ns1.ns.il.        **518400**    IN    A    194.146.106.122|
|ilns.ilan.net.il.    **172800**    IN    A    128.139.35.5|ns1.ns.il.        **518400**    IN    AAAA    2001:67c:1010:31:0:0:0:53|
|ns1.ns.il.        **172800**    IN    A    194.146.106.122|ns3.ns.il.        **518400**    IN    A    194.0.11.103|
|ns1.ns.il.        **172800**    IN    AAAA    2001:67c:1010:31:0:0:0:53|ns3.ns.il.        **518400**    IN    AAAA    2001:678:e:103:0:0:0:53|
|ns3.ns.il.        **172800**    IN    A    194.0.11.103|ns4.ns.il.        **518400**    IN    A    204.61.216.134|
|ns3.ns.il.        **172800**    IN    AAAA    2001:678:e:103:0:0:0:53|ns4.ns.il.        **518400**    IN    AAAA    2001:500:14:6134:ad:0:0:1|
|ns4.ns.il.        **172800**    IN    A    204.61.216.134|nsa.ns.il.        **518400**    IN    A    192.115.7.53|
|ns4.ns.il.        **172800**    IN    AAAA    2001:500:14:6134:ad:0:0:1|nsb.ns.il.        **518400**    IN    A    192.115.7.60|
|nsa.ns.il.        **172800**    IN    A    192.115.7.53|nse.ns.il.        **518400**    IN    A    192.115.141.253|
|nsb.ns.il.        **172800**    IN    A    192.115.7.60||
|nse.ns.il.        **172800**    IN    A    192.115.141.253||
#
## bestbuy
|expected|actual|
|--------|---|
|bestbuy.        86400    IN    DS    **1501** **8** 2 **6E98E0865F6A8CD3E69F0A03CB0D9D80333A31D113AD85BBA7571F87262C5D32**|bestbuy.        86400    IN    DS    **57538** **7** **1 A2206459743A9D928DEBB911DBE3EA192A70EFA2**|
|a0.nic.bestbuy.        **172800**    IN    A    65.22.216.9|**bestbuy.        86400    IN    DS    57538 7 **2 **754902A9893DB0FF2E37B44564121CB80C685CF3267BCAE715A07E12151BA8D8**|
|a0.nic.bestbuy.        **172800**    IN    AAAA    2a01:8840:d2:0:0:0:0:9|a0.nic.bestbuy.        **518400**    IN    A    65.22.216.9|
|a2.nic.bestbuy.        **172800**    IN    A    65.22.219.9|a0.nic.bestbuy.        **518400**    IN    AAAA    2a01:8840:d2:0:0:0:0:9|
|a2.nic.bestbuy.        **172800**    IN    AAAA    2a01:8840:d5:0:0:0:0:9|a2.nic.bestbuy.        **518400**    IN    A    65.22.219.9|
|b0.nic.bestbuy.        **172800**    IN    A    65.22.217.9|a2.nic.bestbuy.        **518400**    IN    AAAA    2a01:8840:d5:0:0:0:0:9|
|b0.nic.bestbuy.        **172800**    IN    AAAA    2a01:8840:d3:0:0:0:0:9|b0.nic.bestbuy.        **518400**    IN    A    65.22.217.9|
|c0.nic.bestbuy.        **172800**    IN    A    65.22.218.9|b0.nic.bestbuy.        **518400**    IN    AAAA    2a01:8840:d3:0:0:0:0:9|
|c0.nic.bestbuy.        **172800**    IN    AAAA    2a01:8840:d4:0:0:0:0:9|c0.nic.bestbuy.        **518400**    IN    A    65.22.218.9|
||c0.nic.bestbuy.        **518400**    IN    AAAA    2a01:8840:d4:0:0:0:0:9|
#
## io
|expected|actual|
|--------|---|
|a0.nic.io.        **172800**    IN    A    65.22.160.17|**io.            86400    IN    DS    57355 8 1 434E91E206134F5B3B0AC603B26F5E029346ABC9**|
|a0.nic.io.        **172800**    IN    AAAA    2a01:8840:9e:0:0:0:0:17|a0.nic.io.        **518400**    IN    A    65.22.160.17|
|a2.nic.io.        **172800**    IN    A    65.22.163.17|a0.nic.io.        **518400**    IN    AAAA    2a01:8840:9e:0:0:0:0:17|
|**a2**.nic.io.        **172800**    IN    AAAA    **2a01:8840:a1:0:0:0:0:17**|a2.nic.io.        **518400**    IN    **AAAA    2a01:8840:a1:0:0:0:0:17**|
|b0.nic.io.        **172800**    IN    A    65.22.161.17|**a2.nic.io.        518400    IN    **A    65.22.163.17|
|**b0**.nic.io.        **172800**    IN    AAAA    **2a01:8840:9f:0:0:0:0:17**|**b0**.nic.io.        **518400**    IN    AAAA    **2a01:8840:9f:0:0:0:0:17**|
|c0.nic.io.        **172800**    IN    A    65.22.162.17|b0.nic.io.        **518400**    IN    A    65.22.161.17|
|**c0.nic.io.        172800    IN    AAAA    2a01:8840:a0:0:0:0:0:17**|**c0**.nic.io.        **518400**    IN    AAAA    **2a01:8840:a0:0:0:0:0:17**|
||c0.nic.io.        **518400**    IN    A    65.22.162.17|
#
## iq
|expected|actual|
|--------|---|
|**iq.            172800    IN    NS    iq.cctld.authdns.ripe.net.**||
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|ns.cocca.fr.        **518400**    IN    **A**    **185.17.236.123**|
|**ns1**.**cmc**.**iq**.        **172800**    IN    **A**    **194.117.57.100**|**ns**.**cocca**.**fr**.        **518400**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:93**|
|**nsp-anycast**.cmc.iq.    **172800**    IN    A    194.117.**58**.**42**|**ns1**.cmc.iq.        **518400**    IN    A    194.117.**57**.**100**|
|nsp-anycast.cmc.iq.    **172800**    IN    AAAA    2001:500:14:8001:ad:0:0:42|nsp-anycast.cmc.iq.    **518400**    IN    AAAA    2001:500:14:8001:ad:0:0:42|
|**iq**.**cctld**.**authdns**.**ripe.net.**    **172800**    IN    A    **193**.**0**.**9**.**81**|**nsp-anycast**.**cmc**.**iq**.    **518400**    IN    A    **194**.**117**.**58**.**42**|
|**iq.cctld.authdns.ripe.net.    172800    IN    AAAA    2001:67c:e0:0:0:0:0:81**||
#
## autos
|expected|actual|
|--------|---|
|**autos.            86400    IN    DS    28189 7 2 474241A09E9E9C76BF43474111D7741AE482E89838A8059CDE4A7236994C664E**|a0.nic.autos.        **518400**    IN    A    65.22.100.9|
|a0.nic.autos.        **172800**    IN    A    65.22.100.9|a0.nic.autos.        **518400**    IN    AAAA    2a01:8840:62:0:0:0:0:9|
|a0.nic.autos.        **172800**    IN    AAAA    2a01:8840:62:0:0:0:0:9|a2.nic.autos.        **518400**    IN    **AAAA**    **2a01:8840:65:0:0:0:0:9**|
|a2.nic.autos.        **172800**    IN    **A**    **65.22.103.9**|a2.nic.autos.        **518400**    IN    **A**    **65.22.103.9**|
|a2.nic.autos.        **172800**    IN    **AAAA**    **2a01:8840:65:0:0:0:0:9**|b0.nic.autos.        **518400**    IN    A    65.22.101.9|
|b0.nic.autos.        **172800**    IN    A    65.22.101.9|b0.nic.autos.        **518400**    IN    AAAA    2a01:8840:63:0:0:0:0:9|
|b0.nic.autos.        **172800**    IN    AAAA    2a01:8840:63:0:0:0:0:9|c0.nic.autos.        **518400**    IN    **AAAA**    **2a01:8840:64:0:0:0:0:9**|
|c0.nic.autos.        **172800**    IN    **A**    **65.22.102.9**|c0.nic.autos.        **518400**    IN    **A**    **65.22.102.9**|
|c0.nic.autos.        **172800**    IN    **AAAA**    **2a01:8840:64:0:0:0:0:9**||
#
## xn--5su34j936bgsg
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bosch
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ups
|expected|actual|
|--------|---|
|ups.            86400    IN    DS    **2002** **8** **2** **28E49220A4B3BC519F2CD5800B8C96DB682A9651EEC3BB19FF98D670CBE4BE36**|ups.            86400    IN    DS    **1863** **7** **1** **4984BE9EA29CD9B939FCF553BA462FA634803DC2**|
|**a0.nic.**ups.        **172800**    IN    **A**    **65.22.240.1**|ups.            **86400**    IN    **DS**    **1863** **7 2 9E9C0183B9FF4236950B4F4AE29E21845D55A676FD8B17D8821CF46FD2FBD603**|
|a0.nic.ups.        **172800**    IN    AAAA    2a01:8840:ea:0:0:0:0:1|a0.nic.ups.        **518400**    IN    AAAA    2a01:8840:ea:0:0:0:0:1|
|**a2**.nic.ups.        **172800**    IN    A    65.22.**243**.1|**a0**.nic.ups.        **518400**    IN    A    65.22.**240**.1|
|a2.nic.ups.        **172800**    IN    AAAA    2a01:8840:ed:0:0:0:0:1|a2.nic.ups.        **518400**    IN    AAAA    2a01:8840:ed:0:0:0:0:1|
|**b0**.nic.ups.        **172800**    IN    A    65.22.**241**.1|**a2**.nic.ups.        **518400**    IN    A    65.22.**243**.1|
|b0.nic.ups.        **172800**    IN    AAAA    2a01:8840:eb:0:0:0:0:1|b0.nic.ups.        **518400**    IN    AAAA    2a01:8840:eb:0:0:0:0:1|
|**c0**.nic.ups.        **172800**    IN    A    65.22.**242**.1|**b0**.nic.ups.        **518400**    IN    A    65.22.**241**.1|
|c0.nic.ups.        **172800**    IN    AAAA    2a01:8840:ec:0:0:0:0:1|c0.nic.ups.        **518400**    IN    AAAA    2a01:8840:ec:0:0:0:0:1|
||**c0.nic.ups.        518400    IN    A    65.22.242.1**|
#
## je
|expected|actual|
|--------|---|
|**je.            172800    IN    NS    e.ci-servers.net.**||
|je.            172800    IN    NS    **dns2**.**nominetdns**.**uk**.|je.            172800    IN    NS    **e**.**ci-servers**.**gg**.|
|je.            172800    IN    NS    **dns3**.**nominetdns**.**uk**.|je.            172800    IN    NS    **f**.**ci-servers**.**je**.|
|je.            172800    IN    NS    **dns4**.**nominetdns**.**uk**.|je.            172800    IN    NS    **ns0**.**ja**.**net**.|
|**je**.            **86400**    IN    **DS**    **19054** **8 2 051F21016E36C0DC46DA9437C9F5975A95BF6B0B85E9E8BF53F49930EB65E90D**|**e**.**ci-servers.gg.**    **518400**    IN    **AAAA**    **2001:500:14:6074:ad:0:0:1**|
|e.ci-servers.**net**.    **172800**    IN    A    204.61.216.74|e.ci-servers.**gg**.    **518400**    IN    A    204.61.216.74|
|**e**.ci-servers.**net**.    **172800**    IN    **AAAA**    **2001:500:14:6074:ad:0:0:1**|**f**.ci-servers.**je**.    **518400**    IN    **A**    **213**.**248**.**223**.**254**|
|**ns99**.**dns**.**net**.**nz**.    **172800**    IN    **A**    **202.46.190.131**|**f**.**ci-servers.je.**    **518400**    IN    **AAAA**    **2a01:618:407:0:0:0:0:254**|
|**ns99**.**dns**.net.**nz.**    **172800**    IN    **AAAA**    **2001:dce:2000:2:0:0:0:131**|**ns0**.**ja**.net.        **518400**    IN    **A**    **193.63.94.20**|
|**c**.**ci-servers**.**org**.    **172800**    IN    A    **194**.**146**.**106**.**86**|**ns0**.**ja**.**net**.        **518400**    IN    A    **128**.**86**.**1**.**20**|
|**c**.**ci-servers**.**org**.    **172800**    IN    AAAA    **2001:67c:1010:22:0:0:0:53**|**ns0**.**ja**.**net**.        **518400**    IN    AAAA    **2001:630:0:8:0:0:0:14**|
|**dns1**.**nominetdns**.**uk**.    **172800**    IN    **A**    **213.248.219.254**|**ns0**.**ja**.**net**.        **518400**    IN    **AAAA**    **2001:630:0:9:0:0:0:14**|
|**dns1**.**nominetdns**.**uk**.    **172800**    IN    AAAA    **2a01:618:403:0:0:0:0:254**|**ns99**.**dns**.**net**.**nz.**    **518400**    IN    AAAA    **2001:dce:2000:2:0:0:0:131**|
|**dns2**.**nominetdns**.**uk**.    **172800**    IN    A    **103**.**49**.**83**.**254**|**ns99**.**dns**.**net**.**nz.**    **518400**    IN    A    **202**.**46**.**190**.**131**|
|**dns2**.**nominetdns**.**uk**.    **172800**    IN    AAAA    **2401:fd80:403:0:0:0:0:254**|**c**.**ci-servers**.**org**.    **518400**    IN    AAAA    **2001:67c:1010:22:0:0:0:53**|
|**dns3**.**nominetdns**.**uk**.    **172800**    IN    A    **213**.**248**.**223**.**254**|**c**.**ci-servers**.**org**.    **518400**    IN    A    **194**.**146**.**106**.**86**|
|**dns3**.nominetdns.uk.    **172800**    IN    AAAA    **2a01:618:407:0:0:0:0:254**|**dns1**.nominetdns.uk.    **518400**    IN    AAAA    **2a01:618:403:0:0:0:0:254**|
|**dns4**.nominetdns.uk.    **172800**    IN    A    **43**.**230**.**51**.254|**dns1**.nominetdns.uk.    **518400**    IN    A    **213**.**248**.**219**.254|
|**dns4.nominetdns.uk.    172800    IN    AAAA    2401:fd80:407:0:0:0:0:254**||
#
## capitalone
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## jaguar
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--t60b56a
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## trading
|expected|actual|
|--------|---|
|trading.        **86400**    IN    **DS**    **45886** **8** **2** **27A7DA05164AEE70F59BD61A8C3B2C8CE7F4785FB6D321B9A55400A22C8B96C7**|trading.        **172800**    IN    **NS**    **ac1.nstld.com.**|
||**trading.**        **172800**    **IN    NS    ac2.nstld.com.**|
||**trading.        172800    IN    NS    ac3.nstld.com.**|
||**trading.        172800    IN    NS    ac4.nstld.com.**|
|**trading**.**        172800    IN    NS    a**.**nic**.**trading.**|**ac1**.**nstld**.**com**.        **518400**    IN    **A**    **192**.**42**.**176**.**30**|
|**trading.**        **172800    **IN    **NS**    **b**.**nic**.**trading**.|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**trading**.**        172800    IN    NS    c**.**nic**.**trading.**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**trading.**        **172800    **IN    **NS    d.nic.trading.**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**a.nic.trading.        172800    IN    **A    **194**.**169**.**218**.**125**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**a**.**nic**.**trading**.        **172800**    IN    AAAA    **2001:67c:13cc:0:0:0:1:125**|**ac4**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:123:0:0:0:0:30**|
|**b**.**nic**.**trading**.        **172800**    IN    A    **185**.**24**.**64**.**125**|**ac4**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**b**.**nic**.**trading**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:125**||
|**c**.**nic**.**trading**.        **172800**    IN    **A    212.18.248.125**||
|**c.nic.trading.        172800    IN    **AAAA    **2a04:2b00:13ee:0:0:0:0:125**||
|**d**.**nic**.**trading**.        **172800**    IN    A    **212**.**18**.**249**.**125**||
|**d.nic.trading.        172800    IN    AAAA    2a04:2b00:13ff:0:0:0:0:125**||
#
## xn--9krt00a
|expected|actual|
|--------|---|
|xn--9krt00a.        86400    IN    DS    **6052** **8** 2 **E5AEA197B5FB7F042833684BBF64FD1F9341BAA2007B2DB2958C9DFAA5884B78**|xn--9krt00a.        86400    IN    DS    **48046** **7** **1 418BE4A49D0E918967EE13542671DCA14495AF66**|
|a0.nic.xn--9krt00a.    **172800**    IN    **A**    **65.22.112.1**|**xn--9krt00a.        86400    IN    DS    48046 7 **2 **CE65E46BB962C0425FCA5B12BE919A4CDC0CD9D535CF58B7EEB3A96CE1611387**|
|a0.nic.xn--9krt00a.    **172800**    IN    **AAAA**    **2a01:8840:6e:0:0:0:0:1**|a0.nic.xn--9krt00a.    **518400**    IN    **AAAA**    **2a01:8840:6e:0:0:0:0:1**|
|a2.nic.xn--9krt00a.    **172800**    IN    A    65.22.115.1|a0.nic.xn--9krt00a.    **518400**    IN    **A**    **65.22.112.1**|
|a2.nic.xn--9krt00a.    **172800**    IN    AAAA    2a01:8840:71:0:0:0:0:1|a2.nic.xn--9krt00a.    **518400**    IN    A    65.22.115.1|
|b0.nic.xn--9krt00a.    **172800**    IN    **A**    **65.22.113.1**|a2.nic.xn--9krt00a.    **518400**    IN    AAAA    2a01:8840:71:0:0:0:0:1|
|b0.nic.xn--9krt00a.    **172800**    IN    **AAAA**    **2a01:8840:6f:0:0:0:0:1**|b0.nic.xn--9krt00a.    **518400**    IN    **AAAA**    **2a01:8840:6f:0:0:0:0:1**|
|c0.nic.xn--9krt00a.    **172800**    IN    A    65.22.114.1|b0.nic.xn--9krt00a.    **518400**    IN    **A**    **65.22.113.1**|
|c0.nic.xn--9krt00a.    **172800**    IN    AAAA    2a01:8840:70:0:0:0:0:1|c0.nic.xn--9krt00a.    **518400**    IN    A    65.22.114.1|
||c0.nic.xn--9krt00a.    **518400**    IN    AAAA    2a01:8840:70:0:0:0:0:1|
#
## lupin
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## jp
|expected|actual|
|--------|---|
|jp.            86400    IN    DS    **46369** 8 2 **39F054DCB3EC1E93D8AE6D8F1AAAD91794055EA36895045FAF6F65F02FEBC579**|jp.            86400    IN    DS    **39595** 8 2 **2871D562754FD45AC0452440D806ABB8E6BA967B2032B166FD2761E873553387**|
|a.dns.jp.        **172800**    IN    A    203.119.1.1|a.dns.jp.        **518400**    IN    A    203.119.1.1|
|a.dns.jp.        **172800**    IN    AAAA    2001:dc4:0:0:0:0:0:1|a.dns.jp.        **518400**    IN    AAAA    2001:dc4:0:0:0:0:0:1|
|b.dns.jp.        **172800**    IN    A    202.12.30.131|b.dns.jp.        **518400**    IN    A    202.12.30.131|
|b.dns.jp.        **172800**    IN    AAAA    2001:dc2:0:0:0:0:0:1|b.dns.jp.        **518400**    IN    AAAA    2001:dc2:0:0:0:0:0:1|
|c.dns.jp.        **172800**    IN    A    156.154.100.5|c.dns.jp.        **518400**    IN    A    156.154.100.5|
|c.dns.jp.        **172800**    IN    AAAA    2001:502:ad09:0:0:0:0:5|c.dns.jp.        **518400**    IN    AAAA    2001:502:ad09:0:0:0:0:5|
|d.dns.jp.        **172800**    IN    A    210.138.175.244|d.dns.jp.        **518400**    IN    A    210.138.175.244|
|d.dns.jp.        **172800**    IN    AAAA    2001:240:0:0:0:0:0:53|d.dns.jp.        **518400**    IN    AAAA    2001:240:0:0:0:0:0:53|
|e.dns.jp.        **172800**    IN    A    192.50.43.53|e.dns.jp.        **518400**    IN    A    192.50.43.53|
|e.dns.jp.        **172800**    IN    AAAA    2001:200:c000:0:0:0:0:35|e.dns.jp.        **518400**    IN    AAAA    2001:200:c000:0:0:0:0:35|
|f.dns.jp.        **172800**    IN    A    150.100.6.8|f.dns.jp.        **518400**    IN    A    150.100.6.8|
|f.dns.jp.        **172800**    IN    AAAA    2001:2f8:0:100:0:0:0:153|f.dns.jp.        **518400**    IN    AAAA    2001:2f8:0:100:0:0:0:153|
|g.dns.jp.        **172800**    IN    A    203.119.40.1|g.dns.jp.        **518400**    IN    A    203.119.40.1|
|h.dns.jp.        **172800**    IN    A    65.22.40.25|h.dns.jp.        **518400**    IN    A    65.22.40.25|
|h.dns.jp.        **172800**    IN    AAAA    2a01:8840:1ba:0:0:0:0:25|h.dns.jp.        **518400**    IN    AAAA    2a01:8840:1ba:0:0:0:0:25|
#
## dot
|expected|actual|
|--------|---|
|dot.            86400    IN    DS    **52639** **8** 2 **E2BC058F7515C31DFDD8ADED00BA870071AB84E0F32DB3003C533C9A6D4F6F84**|dot.            86400    IN    DS    **31240** **7** **1 9BC8F9DF2406B71A5129200F9F1E2AF8DAA134DD**|
|a0.nic.dot.        **172800**    IN    A    65.22.92.1|**dot.            86400    IN    DS    31240 7 **2 **B6D82A83FF48E896F700CDC24582D02B8D035724750237E40FF4FCC5C37C7E5B**|
|a0.nic.dot.        **172800**    IN    AAAA    2a01:8840:5a:0:0:0:0:1|a0.nic.dot.        **518400**    IN    A    65.22.92.1|
|a2.nic.dot.        **172800**    IN    A    65.22.95.1|a0.nic.dot.        **518400**    IN    AAAA    2a01:8840:5a:0:0:0:0:1|
|a2.nic.dot.        **172800**    IN    AAAA    2a01:8840:5d:0:0:0:0:1|a2.nic.dot.        **518400**    IN    A    65.22.95.1|
|b0.nic.dot.        **172800**    IN    **A**    **65.22.93.1**|a2.nic.dot.        **518400**    IN    AAAA    2a01:8840:5d:0:0:0:0:1|
|b0.nic.dot.        **172800**    IN    **AAAA**    **2a01:8840:5b:0:0:0:0:1**|b0.nic.dot.        **518400**    IN    **AAAA**    **2a01:8840:5b:0:0:0:0:1**|
|c0.nic.dot.        **172800**    IN    A    65.22.94.1|b0.nic.dot.        **518400**    IN    **A**    **65.22.93.1**|
|c0.nic.dot.        **172800**    IN    AAAA    2a01:8840:5c:0:0:0:0:1|c0.nic.dot.        **518400**    IN    A    65.22.94.1|
||c0.nic.dot.        **518400**    IN    AAAA    2a01:8840:5c:0:0:0:0:1|
#
## skin
|expected|actual|
|--------|---|
|skin.            172800    IN    NS    **a**.**nic**.**skin**.|skin.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|skin.            172800    IN    NS    **b**.**nic**.**skin**.|skin.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|skin.            172800    IN    NS    **c**.**nic**.**skin**.|skin.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|skin.            172800    IN    NS    **d**.**nic**.**skin**.|skin.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**skin**.**            86400    IN    DS    24104 8 2 3EAEBED2323950252487A9E9F953157A1BBE8B0B7D82906FCD2816C623778B0A**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**skin.**        **172800**    IN    A    **194**.**169**.**218**.**118**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**a**.**nic**.**skin**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:118**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b.nic.skin.        172800    IN    **A    **185**.**24**.**64**.**118**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**b**.**nic**.**skin**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:118**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**skin**.        **172800**    IN    A    **212**.**18**.**248**.**118**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**c**.**nic**.**skin**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:118**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**skin**.        **172800**    IN    **A**    **212.18.249.118**||
|**d**.**nic**.**skin**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:118**||
#
## leclerc
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## guardian
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ki
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|pch.nic.ki.        **172800**    IN    A    204.61.216.26|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|pch.nic.ki.        **172800**    IN    AAAA    2001:500:14:6026:ad:0:0:1|pch.nic.ki.        **518400**    IN    A    204.61.216.26|
||pch.nic.ki.        **518400**    IN    AAAA    2001:500:14:6026:ad:0:0:1|
#
## kn
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|pch.nic.kn.        **172800**    IN    A    204.61.216.109|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|pch.nic.kn.        **172800**    IN    AAAA    2001:500:14:6109:ad:0:0:1|pch.nic.kn.        **518400**    IN    A    204.61.216.109|
|ns.coccaregistry.org.    **172800**    IN    A    185.17.236.111|pch.nic.kn.        **518400**    IN    AAAA    2001:500:14:6109:ad:0:0:1|
|ns.coccaregistry.org.    **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:111|ns.coccaregistry.org.    **518400**    IN    A    185.17.236.111|
||ns.coccaregistry.org.    **518400**    IN    AAAA    2a03:dd40:3:0:0:0:0:111|
#
## xn--mgbc0a9azcg
|expected|actual|
|--------|---|
|**xn--mgbc0a9azcg.    172800    IN    NS    f.tld.ma.**||
|ns-ma.nic.fr.        **172800**    IN    **A**    **194.0.9.1**|ns-ma.nic.fr.        **518400**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|
|ns-ma.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|ns-ma.nic.fr.        **518400**    IN    **A**    **194.0.9.1**|
|a.tld.ma.        **172800**    IN    A    81.192.171.83|a.tld.ma.        **518400**    IN    A    81.192.171.83|
|a.tld.ma.        **172800**    IN    A    81.192.171.131|a.tld.ma.        **518400**    IN    A    81.192.171.131|
|a.tld.ma.        **172800**    IN    AAAA    2001:4288:1800:186:0:0:0:3|a.tld.ma.        **518400**    IN    AAAA    2001:4288:1800:186:0:0:0:3|
|b.tld.ma.        **172800**    IN    **A**    **81.192.171.84**|b.tld.ma.        **518400**    IN    **AAAA**    **2001:4288:1800:186:0:0:0:4**|
|b.tld.ma.        **172800**    IN    A    81.192.171.132|b.tld.ma.        **518400**    IN    A    81.192.171.132|
|b.tld.ma.        **172800**    IN    **AAAA**    **2001:4288:1800:186:0:0:0:4**|b.tld.ma.        **518400**    IN    **A**    **81.192.171.84**|
|c.tld.ma.        **172800**    IN    A    81.192.171.115|c.tld.ma.        **518400**    IN    A    81.192.171.115|
|c.tld.ma.        **172800**    IN    A    81.192.171.139|c.tld.ma.        **518400**    IN    A    81.192.171.139|
|c.tld.ma.        **172800**    IN    AAAA    2001:4288:1800:386:0:0:0:3|c.tld.ma.        **518400**    IN    AAAA    2001:4288:1800:386:0:0:0:3|
|d.tld.ma.        **172800**    IN    A    81.192.171.116|d.tld.ma.        **518400**    IN    A    81.192.171.116|
|d.tld.ma.        **172800**    IN    A    81.192.171.140|d.tld.ma.        **518400**    IN    A    81.192.171.140|
|d.tld.ma.        **172800**    IN    AAAA    2001:4288:1800:386:0:0:0:4|d.tld.ma.        **518400**    IN    AAAA    2001:4288:1800:386:0:0:0:4|
|e.tld.ma.        **172800**    IN    A    105.73.80.236|e.tld.ma.        **518400**    IN    A    105.73.80.236|
|**f.tld.ma.        172800    IN    A    41.214.240.4**||
#
## kw
|expected|actual|
|--------|---|
|**kw.            172800    IN    NS    c.nic.kw.**||
|**kw.            172800    IN    NS    d.nic.kw.**||
|a.nic.kw.        **172800**    IN    A    51.141.6.252|a.nic.kw.        **518400**    IN    A    51.141.6.252|
|b.nic.kw.        **172800**    IN    A    **168**.**187**.**100**.**84**|b.nic.kw.        **518400**    IN    A    **23**.**97**.**177**.**111**|
|**c**.nic.kw.        **172800**    IN    A    **194.58.198.135**|**e**.nic.kw.        **518400**    IN    A    185.**17**.**236**.**93**|
|**c.nic.kw.        172800    IN    AAAA    2a01:3f1:3032:8001:0:0:0:135**|**e**.nic.kw.        **518400**    IN    AAAA    **2a03:dd40:3:0:0:0:0:93**|
|**d.nic.kw.        172800    IN    A    **185.**42**.**137**.**135**|**pch**.nic.kw.        **518400**    IN    AAAA    **2001:500:14:6118:ad:0:0:1**|
|**d**.nic.kw.        **172800**    IN    AAAA    **2a01:3f0:400:8001:0:0:0:135**|pch.nic.kw.        **518400**    IN    A    204.61.216.118|
|**e**.nic.kw.        **172800**    IN    **A    185.17.236.93**||
|**e.nic.kw.        172800    IN    **AAAA    **2a03:dd40:3:0:0:0:0:93**||
|pch.nic.kw.        **172800**    IN    A    204.61.216.118||
|**pch.nic.kw.        172800    IN    AAAA    2001:500:14:6118:ad:0:0:1**||
#
## off
|expected|actual|
|--------|---|
|**off.            86400    IN    DS    3981 8 2 AB916F2212D2C61310D52DFD63CFA7B027E1C6EAF20BFD7EE09CD0EDA3CD94D9**||
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|**off.            86400    IN    DS    3981 8 2 AB916F2212D2C61310D52DFD63CFA7B027E1C6EAF20BFD7EE09CD0EDA3CD94D9**|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
#
## kerryhotels
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## lc
|expected|actual|
|--------|---|
|lc.            86400    IN    DS    **28069** **8** 2 **A729B4E0D245D3CC81FC71893943DF13F55C26D8415AA042C5ADFF42C76D25DE**|lc.            86400    IN    DS    **31275** **7** **1 8FFD793EA49828F8FAE71E6EAF8CD2A6A329361F**|
|a0.cctld.afilias-nst.info.    **172800**    IN    A    199.254.59.1|**lc.            86400    IN    DS    31275 7 **2 **611D7AF20FB91770B598BFFE4DFDAAFE29F106EFCDE36387F4963700A77622EE**|
|a0.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:1|a0.cctld.afilias-nst.info.    **518400**    IN    A    199.254.59.1|
|a2.cctld.afilias-nst.info.    **172800**    IN    A    199.249.116.1|a0.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:1|
|a2.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:1|a2.cctld.afilias-nst.info.    **518400**    IN    A    199.249.116.1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **A**    **199.254.61.1**|a2.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|c0.cctld.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.60.1|c0.cctld.afilias-nst.info.    **518400**    IN    **A**    **199.254.61.1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:26:0:0:0:0:1|b0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.60.1|
|b2.cctld.afilias-nst.org.    **172800**    IN    A    199.249.124.1|b0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:26:0:0:0:0:1|
|b2.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4c:0:0:0:0:1|b2.cctld.afilias-nst.org.    **518400**    IN    A    199.249.124.1|
|d0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.62.1|b2.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4c:0:0:0:0:1|
|d0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:1|d0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.62.1|
||d0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:1|
#
## travelersinsurance
|expected|actual|
|--------|---|
|travelersinsurance.    86400    IN    DS    **11389** **8** 2 **1A8F262DDBE7316233E999F81AE452C17B3435C57BAB9CEEC4BAE518F121E1F1**|travelersinsurance.    86400    IN    DS    **61570** **7** **1 215C71A2673634E20414F560CC9D441D17AC842A**|
|a0.nic.travelersinsurance.    **172800**    IN    A    65.22.200.17|**travelersinsurance.    86400    IN    DS    61570 7 **2 **10DF2B1439BFCE8E31D758BA494F3FAA6C6317B6BD805A7E6F7850F5318B63BB**|
|a0.nic.travelersinsurance.    **172800**    IN    AAAA    2a01:8840:c2:0:0:0:0:17|a0.nic.travelersinsurance.    **518400**    IN    A    65.22.200.17|
|a2.nic.travelersinsurance.    **172800**    IN    **A**    **65.22.203.17**|a0.nic.travelersinsurance.    **518400**    IN    AAAA    2a01:8840:c2:0:0:0:0:17|
|a2.nic.travelersinsurance.    **172800**    IN    **AAAA**    **2a01:8840:c5:0:0:0:0:17**|a2.nic.travelersinsurance.    **518400**    IN    **AAAA**    **2a01:8840:c5:0:0:0:0:17**|
|b0.nic.travelersinsurance.    **172800**    IN    A    65.22.201.17|a2.nic.travelersinsurance.    **518400**    IN    **A**    **65.22.203.17**|
|b0.nic.travelersinsurance.    **172800**    IN    AAAA    2a01:8840:c3:0:0:0:0:17|b0.nic.travelersinsurance.    **518400**    IN    A    65.22.201.17|
|c0.nic.travelersinsurance.    **172800**    IN    A    65.22.202.17|b0.nic.travelersinsurance.    **518400**    IN    AAAA    2a01:8840:c3:0:0:0:0:17|
|c0.nic.travelersinsurance.    **172800**    IN    AAAA    2a01:8840:c4:0:0:0:0:17|c0.nic.travelersinsurance.    **518400**    IN    A    65.22.202.17|
||c0.nic.travelersinsurance.    **518400**    IN    AAAA    2a01:8840:c4:0:0:0:0:17|
#
## li
|expected|actual|
|--------|---|
|li.            86400    IN    DS    **62844** 13 2 **1A0BE40AA38A254F97CDF811ACB4E33872A087E718FD3BA3828E3D59C706C3E4**|li.            86400    IN    DS    **30904** 13 2 **63725534B907CFC0E2326A640327C70C8E44D747AABEEF0D1A14AFB7836A7894**|
|a.nic.li.        **172800**    IN    A    130.59.31.42|a.nic.li.        **518400**    IN    A    130.59.31.42|
|a.nic.li.        **172800**    IN    AAAA    2001:620:0:ff:0:0:0:57|a.nic.li.        **518400**    IN    AAAA    2001:620:0:ff:0:0:0:57|
|b.nic.li.        **172800**    IN    A    130.59.31.44|b.nic.li.        **518400**    IN    A    130.59.31.44|
|b.nic.li.        **172800**    IN    AAAA    2001:620:0:ff:0:0:0:59|b.nic.li.        **518400**    IN    AAAA    2001:620:0:ff:0:0:0:59|
|c.nic.li.        **172800**    IN    A    74.116.178.40|c.nic.li.        **518400**    IN    A    74.116.178.40|
|c.nic.li.        **172800**    IN    AAAA    2620:7d:e000:0:0:0:0:28|c.nic.li.        **518400**    IN    AAAA    2620:7d:e000:0:0:0:0:28|
|e.nic.li.        **172800**    IN    A    194.0.17.1|e.nic.li.        **518400**    IN    A    194.0.17.1|
|e.nic.li.        **172800**    IN    AAAA    2001:678:3:0:0:0:0:1|e.nic.li.        **518400**    IN    AAAA    2001:678:3:0:0:0:0:1|
|f.nic.li.        **172800**    IN    A    194.146.106.14|f.nic.li.        **518400**    IN    A    194.146.106.14|
|f.nic.li.        **172800**    IN    AAAA    2001:67c:1010:3:0:0:0:53|f.nic.li.        **518400**    IN    AAAA    2001:67c:1010:3:0:0:0:53|
|g.nic.li.        **172800**    IN    A    194.0.1.40|g.nic.li.        **518400**    IN    A    194.0.1.40|
|g.nic.li.        **172800**    IN    AAAA    2001:678:4:0:0:0:0:28|g.nic.li.        **518400**    IN    AAAA    2001:678:4:0:0:0:0:28|
|h.nic.li.        **172800**    IN    **A**    **85.119.5.230**|h.nic.li.        **518400**    IN    **AAAA**    **2a03:bd80:36:0:0:1:203:230**|
|h.nic.li.        **172800**    IN    **AAAA**    **2a03:bd80:36:0:0:1:203:230**|h.nic.li.        **518400**    IN    **A**    **85.119.5.230**|
#
## fun
|expected|actual|
|--------|---|
|fun.            172800    IN    NS    **e**.nic.fun.|fun.            172800    IN    NS    **c**.nic.fun.|
|fun.            172800    IN    NS    **f**.nic.fun.|fun.            172800    IN    NS    **d**.nic.fun.|
|a.nic.fun.        **172800**    IN    A    194.169.218.72|a.nic.fun.        **518400**    IN    A    194.169.218.72|
|a.nic.fun.        **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:72|a.nic.fun.        **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:72|
|b.nic.fun.        **172800**    IN    **A**    **185.24.64.72**|b.nic.fun.        **518400**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:72**|
|b.nic.fun.        **172800**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:72**|b.nic.fun.        **518400**    IN    **A**    **185.24.64.72**|
|**e**.nic.fun.        **172800**    IN    A    **212**.**18**.**248**.**72**|**c**.nic.fun.        **518400**    IN    A    **185**.**38**.**99**.**12**|
|**e**.nic.fun.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:72**|**c**.nic.fun.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:12**|
|**f**.nic.fun.        **172800**    IN    A    **212**.**18**.**249**.**72**|**d**.nic.fun.        **518400**    IN    A    **108**.**59**.**161**.**12**|
|**f**.nic.fun.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:72**|**d**.nic.fun.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:12**|
#
## auto
|expected|actual|
|--------|---|
|**auto.            172800    IN    NS    a.nic.auto.**||
|**auto.            172800    IN    NS    b.nic.auto.**||
|**auto.            172800    IN    NS    c.nic.auto.**||
|**auto.            172800    IN    NS    d.nic.auto.**||
||**auto.            86400    IN    DS    64844 5 1 AC3C5E71CC4826ABD69124F6486D1E4D3844BD40**|
||**auto.            86400    IN    DS    64844 5 2 D8EF1F66F30CDB6A3CD311F9E8DFE1F1FA4B10D98992D07E8DA618E5774B7BFD**|
||**auto.            86400    IN    DS    12796 5 2 478BDF9D17C3D08B8EAC59B810562878B5A7193862136FD9401B0A869D5FB4C7**|
|**auto**.**            86400    IN    DS    12796 5 2 478BDF9D17C3D08B8EAC59B810562878B5A7193862136FD9401B0A869D5FB4C7**|**ns2**.**uniregistry**.**info**.    **518400**    IN    A    64.**96**.**2**.**1**|
|**auto**.**            86400    IN    DS    41492 5 1 4EF1EDDD59DAEE765CD1ED0205081D46D25BBE7C**|**ns4**.uniregistry.info.    **518400**    IN    **AAAA**    **2620:10a:80ab:0:0:0:0:3**|
|**auto**.            **86400**    IN    **DS    41492 5 2 01B3B92918B955D84A70F1BC254513D6FD90A33E8ABABC0AAFCF8830AC259C2C**|ns4.uniregistry.info.    **518400**    IN    A    185.159.198.3|
|**a.nic.auto.        172800    IN    **A    **194.169.218.131**|**ns1**.uniregistry.**net**.    **518400**    IN    AAAA    **2620:57:4000:1:0:0:0:1**|
|**a.nic.auto.        172800    IN    AAAA    2001:67c:13cc:0:0:0:1:131**|ns1.uniregistry.net.    **518400**    IN    A    64.96.1.1|
|**b.nic.auto.        172800    IN    A    185.24.**64.**131**|ns3.uniregistry.net.    **518400**    IN    A    185.159.197.3|
|**b**.**nic**.**auto.**        **172800    IN    AAAA    2a04:2b00:13cc:0:0:0:1:131**|ns3.uniregistry.net.    **518400**    IN    AAAA    2620:10a:80aa:0:0:0:0:3|
|**c**.**nic.auto.        172800    IN    A    212.18.248.131**||
|**c.nic.auto.        172800    IN    AAAA    2a04:2b00:13ee:0:0:0:0:131**||
|**d.nic.auto.        172800    IN    AAAA    2a04:2b00:13ff:0:0:0:0:131**||
|**d.nic.auto.        172800    IN    A    212.18.249.131**||
|**ns2.**uniregistry.info.    **172800**    IN    **A**    **64.96.2.1**||
|ns4.uniregistry.info.    **172800**    IN    A    185.159.198.3||
|**ns4**.uniregistry.**info**.    **172800**    IN    AAAA    **2620:10a:80ab:0:0:0:0:3**||
|ns1.uniregistry.net.    **172800**    IN    A    64.96.1.1||
|**ns1.uniregistry.net.    172800    IN    AAAA    2620:57:4000:1:0:0:0:1**||
|ns3.uniregistry.net.    **172800**    IN    A    185.159.197.3||
|ns3.uniregistry.net.    **172800**    IN    AAAA    2620:10a:80aa:0:0:0:0:3||
#
## maif
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bms
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--9et52u
|expected|actual|
|--------|---|
|**xn--9et52u.        86400    IN    DS    769 8 2 2BAE7BA36EA94541B8BC12188EB1AA933B5081CC281909CC5874AF2EBEEBAE96**||
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|**xn--9et52u.        86400    IN    DS    769 8 2 2BAE7BA36EA94541B8BC12188EB1AA933B5081CC281909CC5874AF2EBEEBAE96**|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
||j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## locker
|expected|actual|
|--------|---|
|locker.            86400    IN    DS    **6301** **8** 2 **2A62E4284AD1157A9994BE5022A76CF66C2C233CEEDE058C673D065FEE63B90E**|locker.            86400    IN    DS    **54879** **7** **1 F8C9CD832185B0AB8AE8EB4D621EDE101797D28D**|
|a0.nic.locker.        **172800**    IN    A    65.22.96.33|**locker.            86400    IN    DS    54879 7 **2 **0C069572FB6C734D7D753972461C9A72B3A6AAEB1F09BF6A0F41078CDE97D570**|
|a0.nic.locker.        **172800**    IN    AAAA    2a01:8840:5e:0:0:0:0:33|a0.nic.locker.        **518400**    IN    A    65.22.96.33|
|a2.nic.locker.        **172800**    IN    A    65.22.99.33|a0.nic.locker.        **518400**    IN    AAAA    2a01:8840:5e:0:0:0:0:33|
|a2.nic.locker.        **172800**    IN    AAAA    2a01:8840:61:0:0:0:0:33|a2.nic.locker.        **518400**    IN    A    65.22.99.33|
|b0.nic.locker.        **172800**    IN    A    65.22.97.33|a2.nic.locker.        **518400**    IN    AAAA    2a01:8840:61:0:0:0:0:33|
|**b0**.nic.locker.        **172800**    IN    AAAA    **2a01:8840:5f:0:0:0:0:33**|b0.nic.locker.        **518400**    IN    **AAAA    2a01:8840:5f:0:0:0:0:33**|
|c0.nic.locker.        **172800**    IN    A    65.22.98.33|**b0.nic.locker.        518400    IN    **A    65.22.97.33|
|**c0.nic.locker.        172800    IN    AAAA    2a01:8840:60:0:0:0:0:33**|**c0**.nic.locker.        **518400**    IN    AAAA    **2a01:8840:60:0:0:0:0:33**|
||c0.nic.locker.        **518400**    IN    A    65.22.98.33|
#
## nextdirect
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ma
|expected|actual|
|--------|---|
|**ma.            172800    IN    NS    e.tld.ma.**||
|**ma.            172800    IN    NS    f.tld.ma.**||
||**ma.            172800    IN    NS    e.tld.ma.**|
|dns.inria.fr.        **172800**    IN    A    193.51.208.13|dns.inria.fr.        **518400**    IN    A    193.51.208.13|
|ns-ma.nic.fr.        **172800**    IN    **A**    **194.0.9.1**|ns-ma.nic.fr.        **518400**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|
|ns-ma.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|ns-ma.nic.fr.        **518400**    IN    **A**    **194.0.9.1**|
|a.tld.ma.        **172800**    IN    A    81.192.171.83|a.tld.ma.        **518400**    IN    A    81.192.171.83|
|a.tld.ma.        **172800**    IN    A    81.192.171.131|a.tld.ma.        **518400**    IN    A    81.192.171.131|
|a.tld.ma.        **172800**    IN    AAAA    2001:4288:1800:186:0:0:0:3|a.tld.ma.        **518400**    IN    AAAA    2001:4288:1800:186:0:0:0:3|
|b.tld.ma.        **172800**    IN    **A**    **81.192.171.84**|b.tld.ma.        **518400**    IN    **AAAA**    **2001:4288:1800:186:0:0:0:4**|
|b.tld.ma.        **172800**    IN    A    81.192.171.132|b.tld.ma.        **518400**    IN    A    81.192.171.132|
|b.tld.ma.        **172800**    IN    **AAAA**    **2001:4288:1800:186:0:0:0:4**|b.tld.ma.        **518400**    IN    **A**    **81.192.171.84**|
|c.tld.ma.        **172800**    IN    A    81.192.171.115|c.tld.ma.        **518400**    IN    A    81.192.171.115|
|c.tld.ma.        **172800**    IN    A    81.192.171.139|c.tld.ma.        **518400**    IN    A    81.192.171.139|
|c.tld.ma.        **172800**    IN    AAAA    2001:4288:1800:386:0:0:0:3|c.tld.ma.        **518400**    IN    AAAA    2001:4288:1800:386:0:0:0:3|
|d.tld.ma.        **172800**    IN    A    81.192.171.116|d.tld.ma.        **518400**    IN    A    81.192.171.116|
|d.tld.ma.        **172800**    IN    A    81.192.171.140|d.tld.ma.        **518400**    IN    A    81.192.171.140|
|d.tld.ma.        **172800**    IN    AAAA    2001:4288:1800:386:0:0:0:4|d.tld.ma.        **518400**    IN    AAAA    2001:4288:1800:386:0:0:0:4|
|e.tld.ma.        **172800**    IN    A    105.73.80.236|e.tld.ma.        **518400**    IN    A    105.73.80.236|
|**f.tld.ma.        172800    IN    A    41.214.240.4**||
#
## barefoot
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## md
|expected|actual|
|--------|---|
|**md.            172800    IN    NS    nsr.dns.md.**||
|nsc.dns.md.        **172800**    IN    **A**    **144.217.93.2**|nsc.dns.md.        **518400**    IN    **AAAA**    **2607:5300:201:3100:0:0:0:2f69**|
|nsc.dns.md.        **172800**    IN    **AAAA**    **2607:5300:201:3100:0:0:0:2f69**|nsc.dns.md.        **518400**    IN    **A**    **144.217.93.2**|
|nsf.dns.md.        **172800**    IN    A    92.222.76.179|nsf.dns.md.        **518400**    IN    A    92.222.76.179|
|nsf.dns.md.        **172800**    IN    AAAA    2001:41d0:401:3100:0:0:0:7162|nsf.dns.md.        **518400**    IN    AAAA    2001:41d0:401:3100:0:0:0:7162|
|**nsr.dns.md.        172800    IN    A    213.159.210.127**|nsa.tld.md.        **518400**    IN    A    185.108.181.191|
|nsa.tld.md.        **172800**    IN    A    185.108.181.191|nsb.tld.md.        **518400**    IN    A    185.108.181.192|
|nsb.tld.md.        **172800**    IN    A    185.108.181.192||
#
## host
|expected|actual|
|--------|---|
|host.            172800    IN    NS    **e**.nic.host.|host.            172800    IN    NS    **c**.nic.host.|
|host.            172800    IN    NS    **f**.nic.host.|host.            172800    IN    NS    **d**.nic.host.|
|a.nic.host.        **172800**    IN    **A**    **194.169.218.53**|a.nic.host.        **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:53**|
|a.nic.host.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:53**|a.nic.host.        **518400**    IN    **A**    **194.169.218.53**|
|b.nic.host.        **172800**    IN    A    185.24.64.53|b.nic.host.        **518400**    IN    A    185.24.64.53|
|b.nic.host.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:53|b.nic.host.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:53|
|**e**.nic.host.        **172800**    IN    A    **212**.**18**.**248**.**53**|**c**.nic.host.        **518400**    IN    A    **185**.**38**.**99**.**2**|
|**e**.nic.host.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:53**|**c**.nic.host.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:2**|
|**f**.nic.host.        **172800**    IN    A    **212**.**18**.**249**.**53**|**d**.nic.host.        **518400**    IN    A    **108**.**59**.**161**.**2**|
|**f**.nic.host.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:53**|**d**.nic.host.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:2**|
#
## me
|expected|actual|
|--------|---|
|me.            86400    IN    DS    **45352** **8** 2 **7708C8A6D5D72B63214BBFF50CB54553F7E07A1FA5E9074BD8D63C43102D8559**|me.            86400    IN    DS    **2569** **7** **1 09BA1EB4D20402620881FD9848994417800DB26A**|
|a0.nic.me.        **172800**    IN    A    199.253.59.1|**me.            86400    IN    DS    2569 7 **2 **94E798106F033500E67567B197AE9132C0E916764DC743C55A9ECA3C7BF559E2**|
|**a0**.nic.me.        **172800**    IN    AAAA    **2001:500:53:0:0:0:0:1**|a0.nic.me.        **518400**    IN    **AAAA    2001:500:53:0:0:0:0:1**|
|a2.nic.me.        **172800**    IN    A    199.249.119.1|**a0.nic.me.        518400    IN    **A    199.253.59.1|
|**a2**.nic.me.        **172800**    IN    AAAA    **2001:500:47:0:0:0:0:1**|**a2**.nic.me.        **518400**    IN    AAAA    **2001:500:47:0:0:0:0:1**|
|b0.nic.me.        **172800**    IN    A    199.253.60.1|a2.nic.me.        **518400**    IN    A    199.249.119.1|
|**b0.nic.me.        172800    IN    AAAA    2001:500:54:0:0:0:0:1**|**b0**.nic.me.        **518400**    IN    AAAA    **2001:500:54:0:0:0:0:1**|
|b2.nic.me.        **172800**    IN    A    199.249.127.1|b0.nic.me.        **518400**    IN    A    199.253.60.1|
|b2.nic.me.        **172800**    IN    AAAA    2001:500:4f:0:0:0:0:1|b2.nic.me.        **518400**    IN    A    199.249.127.1|
|c0.nic.me.        **172800**    IN    **A**    **199.253.61.1**|b2.nic.me.        **518400**    IN    AAAA    2001:500:4f:0:0:0:0:1|
|c0.nic.me.        **172800**    IN    **AAAA**    **2001:500:55:0:0:0:0:1**|c0.nic.me.        **518400**    IN    **AAAA**    **2001:500:55:0:0:0:0:1**|
||c0.nic.me.        **518400**    IN    **A**    **199.253.61.1**|
#
## nowtv
|expected|actual|
|--------|---|
|nowtv.            86400    IN    DS    **30316** **8** **2** **06BCB6632FC4327BA1D5ABFF7CACA06F7D01FCADEFBA3AEA17DB0839C5C9CC4A**|nowtv.            86400    IN    DS    **970** **7** **1** **D5FBD89412C9B7F3AF039913BA59E3BDEEBEF55B**|
|**a0.nic.**nowtv.        **172800**    IN    **A**    **65.22.172.1**|nowtv.            **86400**    IN    **DS**    **970** **7 2 7F9668652BF0665A0DBBD61AFE041727666616ABB298C9729CBBBB5E892F9752**|
|a0.nic.nowtv.        **172800**    IN    AAAA    2a01:8840:a6:0:0:0:0:1|a0.nic.nowtv.        **518400**    IN    AAAA    2a01:8840:a6:0:0:0:0:1|
|**a2**.nic.nowtv.        **172800**    IN    A    65.22.**175**.1|**a0**.nic.nowtv.        **518400**    IN    A    65.22.**172**.1|
|a2.nic.nowtv.        **172800**    IN    AAAA    2a01:8840:a9:0:0:0:0:1|a2.nic.nowtv.        **518400**    IN    AAAA    2a01:8840:a9:0:0:0:0:1|
|**b0**.nic.nowtv.        **172800**    IN    A    65.22.**173**.1|**a2**.nic.nowtv.        **518400**    IN    A    65.22.**175**.1|
|b0.nic.nowtv.        **172800**    IN    AAAA    2a01:8840:a7:0:0:0:0:1|b0.nic.nowtv.        **518400**    IN    AAAA    2a01:8840:a7:0:0:0:0:1|
|c0.nic.nowtv.        **172800**    IN    A    65.22.174.1|**b0.nic.nowtv.        518400    IN    A    65.22.173.1**|
|c0.nic.nowtv.        **172800**    IN    AAAA    2a01:8840:a8:0:0:0:0:1|c0.nic.nowtv.        **518400**    IN    A    65.22.174.1|
||c0.nic.nowtv.        **518400**    IN    AAAA    2a01:8840:a8:0:0:0:0:1|
#
## lancaster
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## merckmsd
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## mn
|expected|actual|
|--------|---|
|mn.            86400    IN    DS    **22489** **8** 2 **C069CD3E147E1F008FD2394A7112509C96D26094F876E48E56192779E1C47BA6**|mn.            86400    IN    DS    **61299** **7** **1 7AED0B5BF96D4A045071FE60B6B1BE8F41A3D8A4**|
|a0.cctld.afilias-nst.info.    **172800**    IN    A    199.254.59.1|**mn.            86400    IN    DS    61299 7 **2 **35AD84BA39FF62258FE6052F8E31E67C341D6CFA41D38A4698F9F35FB68E30B6**|
|a0.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:1|a0.cctld.afilias-nst.info.    **518400**    IN    A    199.254.59.1|
|a2.cctld.afilias-nst.info.    **172800**    IN    A    199.249.116.1|a0.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:1|
|a2.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:1|a2.cctld.afilias-nst.info.    **518400**    IN    A    199.249.116.1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **A**    **199.254.61.1**|a2.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|c0.cctld.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|
|ns1.magic.mn.        **172800**    IN    A    202.131.0.10|c0.cctld.afilias-nst.info.    **518400**    IN    **A**    **199.254.61.1**|
|ns2.magic.mn.        **172800**    IN    A    202.72.241.5|ns1.magic.mn.        **518400**    IN    A    202.131.0.10|
|ns3.magic.mn.        **172800**    IN    A    202.131.224.80|ns2.magic.mn.        **518400**    IN    A    202.72.241.5|
|ns4.magic.mn.        **172800**    IN    A    218.100.84.26|ns3.magic.mn.        **518400**    IN    A    202.131.224.80|
|b0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.60.1|ns4.magic.mn.        **518400**    IN    A    218.100.84.26|
|b0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:26:0:0:0:0:1|b0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.60.1|
|b2.cctld.afilias-nst.org.    **172800**    IN    A    199.249.124.1|b0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:26:0:0:0:0:1|
|b2.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4c:0:0:0:0:1|b2.cctld.afilias-nst.org.    **518400**    IN    A    199.249.124.1|
|d0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.62.1|b2.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4c:0:0:0:0:1|
|d0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:1|d0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.62.1|
||d0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:1|
#
## cipriani
|expected|actual|
|--------|---|
|cipriani.        86400    IN    DS    **17209** **8** 2 **41ADAC2BF52A4A5EA210CE9DB7AB6114A28CF916F1E06B1F4C3EEE90077D6147**|cipriani.        86400    IN    DS    **20710** **7** **1 F918E435A52AB4FCBD6D130E42BAB3E0CDAB22B9**|
|a0.nic.cipriani.    **172800**    IN    A    65.22.236.41|**cipriani.        86400    IN    DS    20710 7 **2 **B894A5E84537D8A0FCC80F60CD7EB282A465152F60569387ED763943B5EFC3B4**|
|a0.nic.cipriani.    **172800**    IN    AAAA    2a01:8840:e6:0:0:0:0:41|a0.nic.cipriani.    **518400**    IN    A    65.22.236.41|
|a2.nic.cipriani.    **172800**    IN    A    65.22.239.41|a0.nic.cipriani.    **518400**    IN    AAAA    2a01:8840:e6:0:0:0:0:41|
|a2.nic.cipriani.    **172800**    IN    AAAA    2a01:8840:e9:0:0:0:0:41|a2.nic.cipriani.    **518400**    IN    A    65.22.239.41|
|b0.nic.cipriani.    **172800**    IN    A    65.22.237.41|a2.nic.cipriani.    **518400**    IN    AAAA    2a01:8840:e9:0:0:0:0:41|
|**b0**.nic.cipriani.    **172800**    IN    AAAA    **2a01:8840:e7:0:0:0:0:41**|b0.nic.cipriani.    **518400**    IN    **AAAA    2a01:8840:e7:0:0:0:0:41**|
|c0.nic.cipriani.    **172800**    IN    A    65.22.238.41|**b0.nic.cipriani.    518400    IN    **A    65.22.237.41|
|**c0.nic.cipriani.    172800    IN    AAAA    2a01:8840:e8:0:0:0:0:41**|**c0**.nic.cipriani.    **518400**    IN    AAAA    **2a01:8840:e8:0:0:0:0:41**|
||c0.nic.cipriani.    **518400**    IN    A    65.22.238.41|
#
## mq
|expected|actual|
|--------|---|
||**mq.            172800    IN    NS    ns1-fr.mediaserv.net.**|
|ns1-gp.mediaserv.net.    **172800**    IN    A    213.188.172.1|ns1-**fr.mediaserv.net.    518400    IN    A    188.165.38.14**|
|ns1-mq.mediaserv.net.    **172800**    IN    A    213.16.20.3|**ns1-**gp.mediaserv.net.    **518400**    IN    A    213.188.172.1|
||ns1-mq.mediaserv.net.    **518400**    IN    A    213.16.20.3|
#
## spa
|expected|actual|
|--------|---|
|**spa.            172800    IN    NS    a0.nic.spa.**||
|**spa.            172800    IN    NS    a2.nic.spa.**||
|**spa.            172800    IN    NS    b0.nic.spa.**||
|**spa.            172800    IN    NS    c0.nic.spa.**||
|**spa.            86400    IN    DS    11881 8 2 5F494F6958801E119D309BF6CD627C42D1FD04055703AEAAC2C2D1B98DB00B97**||
|**a0.nic.spa.        172800    IN    A    65.22.48.17**||
|**a0.nic.spa.        172800    IN    AAAA    2a01:8840:2e:0:0:0:0:17**||
|**a2.nic.spa.        172800    IN    A    65.22.51.17**||
|**a2.nic.spa.        172800    IN    AAAA    2a01:8840:31:0:0:0:0:17**||
|**b0.nic.spa.        172800    IN    A    65.22.49.17**||
|**b0.nic.spa.        172800    IN    AAAA    2a01:8840:2f:0:0:0:0:17**||
|**c0.nic.spa.        172800    IN    A    65.22.50.17**||
|**c0.nic.spa.        172800    IN    AAAA    2a01:8840:30:0:0:0:0:17**||
#
## ms
|expected|actual|
|--------|---|
|**ms.            172800    IN    NS    ns.cocca.fr.**||
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|**ms.            172800    IN    NS    **ns.cocca.fr.|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|**ns.cocca.fr.**        **518400    **IN    A    185.17.236.93|
|ms-ns.anycast.pch.net.    **172800**    IN    A    204.61.216.33|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|ms-ns.anycast.pch.net.    **172800**    IN    AAAA    2001:500:14:6033:ad:0:0:1|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
||ms-ns.anycast.pch.net.    **518400**    IN    A    204.61.216.33|
||ms-ns.anycast.pch.net.    **518400**    IN    AAAA    2001:500:14:6033:ad:0:0:1|
#
## poker
|expected|actual|
|--------|---|
|poker.            86400    IN    DS    **12856** **8** 2 **571EFC932D4C25E2F41DF9E216B66732F8D17BB7EFD2F6230AF3127948BA167C**|poker.            86400    IN    DS    **45268** **7** 2 **7DFF3F6DE1F872176B78E295FCCD897982658818A3969085B19205852976E5D8**|
|**a0.nic.**poker.        **172800**    IN    **A**    **65.22.20.33**|poker.            **86400**    IN    **DS**    **45268** **7 1 90E4DB8C6E0968D79DE177F72F73718CB7479143**|
|a0.nic.poker.        **172800**    IN    AAAA    2a01:8840:16:0:0:0:0:33|a0.nic.poker.        **518400**    IN    AAAA    2a01:8840:16:0:0:0:0:33|
|**a2**.nic.poker.        **172800**    IN    A    65.22.**23**.33|**a0**.nic.poker.        **518400**    IN    A    65.22.**20**.33|
|a2.nic.poker.        **172800**    IN    AAAA    2a01:8840:19:0:0:0:0:33|a2.nic.poker.        **518400**    IN    AAAA    2a01:8840:19:0:0:0:0:33|
|**b0**.nic.poker.        **172800**    IN    A    65.22.**21**.33|**a2**.nic.poker.        **518400**    IN    A    65.22.**23**.33|
|b0.nic.poker.        **172800**    IN    AAAA    2a01:8840:17:0:0:0:0:33|b0.nic.poker.        **518400**    IN    AAAA    2a01:8840:17:0:0:0:0:33|
|c0.nic.poker.        **172800**    IN    A    65.22.22.33|**b0.nic.poker.        518400    IN    A    65.22.21.33**|
|c0.nic.poker.        **172800**    IN    AAAA    2a01:8840:18:0:0:0:0:33|c0.nic.poker.        **518400**    IN    A    65.22.22.33|
||c0.nic.poker.        **518400**    IN    AAAA    2a01:8840:18:0:0:0:0:33|
#
## vana
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## mx
|expected|actual|
|--------|---|
|**mx.            86400    IN    DS    49357 8 2 0925E7BA821BFA21D835C2E77A028EA377A5D453DEDC2C481B5E7C80BC1BB64F**||
|c.mx-ns.mx.        **172800**    IN    A    192.100.224.1|c.mx-ns.mx.        **518400**    IN    A    192.100.224.1|
|c.mx-ns.mx.        **172800**    IN    AAAA    2001:1258:0:0:0:0:0:1|c.mx-ns.mx.        **518400**    IN    AAAA    2001:1258:0:0:0:0:0:1|
|e.mx-ns.mx.        **172800**    IN    A    189.201.244.1|e.mx-ns.mx.        **518400**    IN    A    189.201.244.1|
|i.mx-ns.mx.        **172800**    IN    A    207.248.68.1|i.mx-ns.mx.        **518400**    IN    A    207.248.68.1|
|m.mx-ns.mx.        **172800**    IN    **A**    **200.94.176.1**|m.mx-ns.mx.        **518400**    IN    **AAAA**    **2001:13c7:7000:0:0:0:0:1**|
|m.mx-ns.mx.        **172800**    IN    **AAAA**    **2001:13c7:7000:0:0:0:0:1**|m.mx-ns.mx.        **518400**    IN    **A**    **200.94.176.1**|
|o.mx-ns.mx.        **172800**    IN    A    200.23.1.1|o.mx-ns.mx.        **518400**    IN    A    200.23.1.1|
|x.mx-ns.mx.        **172800**    IN    A    201.131.252.1|x.mx-ns.mx.        **518400**    IN    A    201.131.252.1|
#
## my
|expected|actual|
|--------|---|
|**my.            86400    IN    DS    174 8 1 E61EFF1CAF6F896D87538F1DC56DB81060A41D6A**||
|**my.            86400    IN    DS    174 8 2 FB9E2F10F50A09E3614A9E6A2C76C1AE7554711E5242B7F516A8078D86ED87B9**||
|**my.            86400    IN    DS    35481 8 1 89DE7930E30966E4FDDBE1C11026677BFD4B5ED6**||
|**my.            86400    IN    DS    35481 8 2 AE555A40F6BDB488EB025822A71C91C94E1F339FDD71E0386561C3C4B7D2B198**||
|**my.            172800    IN    NS    a.nic.my.**||
||**my.            172800    IN    NS    a.nic.my.**|
||**my.            172800    IN    NS    a1.mynic.my.**|
|my.            **172800**    IN    **NS**    **a1**.**nic**.my.|my.            **86400**    IN    **DS**    **174 8 1 E61EFF1CAF6F896D87538F1DC56DB81060A41D6A**|
|a.mynic.centralnic-dns.com.    **172800**    IN    A    194.169.218.114|**my**.**            86400    IN    DS    174 8 2 FB9E2F10F50A09E3614A9E6A2C76C1AE7554711E5242B7F516A8078D86ED87B9**|
|a.mynic.centralnic-dns.com.    **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:114|**my**.**            86400    IN    DS    35481 8 1 89DE7930E30966E4FDDBE1C11026677BFD4B5ED6**|
|b.mynic.centralnic-dns.com.    **172800**    IN    **A**    **185.24.64.114**|my.            **86400    IN    DS    35481 8 2 AE555A40F6BDB488EB025822A71C91C94E1F339FDD71E0386561C3C4B7D2B198**|
|b.mynic.centralnic-dns.com.    **172800**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:114**|a.mynic.centralnic-dns.com.    **518400**    IN    A    194.169.218.114|
|c.mynic.centralnic-dns.com.    **172800**    IN    A    212.18.248.114|a.mynic.centralnic-dns.com.    **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:114|
|c.mynic.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:114|b.mynic.centralnic-dns.com.    **518400**    IN    **AAAA**    **2a04:2b00:13cc:0:0:0:1:114**|
|d.mynic.centralnic-dns.com.    **172800**    IN    A    212.18.249.114|b.mynic.centralnic-dns.com.    **518400**    IN    **A**    **185.24.64.114**|
|d.mynic.centralnic-dns.com.    **172800**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:114|c.mynic.centralnic-dns.com.    **518400**    IN    A    212.18.248.114|
|**a**.**nic**.my.        **172800**    IN    A    **103**.**44**.**108**.**53**|c.mynic.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:114|
|a.nic.my.        **172800**    IN    AAAA    2001:ddc:0:53:0:0:0:53|d.mynic.centralnic-dns.com.    **518400**    IN    A    212.18.249.114|
|**a1**.nic.my.        **172800**    IN    A    **202**.**171**.**47**.**204**|d.mynic.centralnic-dns.com.    **518400**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:114|
||**a1**.**mynic**.my.        **518400**    IN    A    **202**.**171**.**47**.**204**|
||a.nic.my.        **518400**    IN    AAAA    2001:ddc:0:53:0:0:0:53|
||**a**.nic.my.        **518400**    IN    A    **103**.**44**.**108**.**53**|
#
## mormon
|expected|actual|
|--------|---|
|mormon.            86400    IN    DS    **25606** **8** 2 **32BC7847356B87EF6E35D7CA36F19E481361D235C1E4AB7593012DB12280425D**|mormon.            86400    IN    DS    **12568** **7** **1 D6073D22BEDBD7005A0E4781852C4BF9F63007AB**|
|a0.nic.mormon.        **172800**    IN    A    65.22.152.1|**mormon.            86400    IN    DS    12568 7 **2 **A7E4E331BE6631713BA62063A4112B63132BE342C1C38BFF9A33BFD5FC270599**|
|a0.nic.mormon.        **172800**    IN    AAAA    2a01:8840:96:0:0:0:0:1|a0.nic.mormon.        **518400**    IN    A    65.22.152.1|
|a2.nic.mormon.        **172800**    IN    **A**    **65.22.155.1**|a0.nic.mormon.        **518400**    IN    AAAA    2a01:8840:96:0:0:0:0:1|
|a2.nic.mormon.        **172800**    IN    **AAAA**    **2a01:8840:99:0:0:0:0:1**|a2.nic.mormon.        **518400**    IN    **AAAA**    **2a01:8840:99:0:0:0:0:1**|
|b0.nic.mormon.        **172800**    IN    A    65.22.153.1|a2.nic.mormon.        **518400**    IN    **A**    **65.22.155.1**|
|b0.nic.mormon.        **172800**    IN    AAAA    2a01:8840:97:0:0:0:0:1|b0.nic.mormon.        **518400**    IN    A    65.22.153.1|
|c0.nic.mormon.        **172800**    IN    **A**    **65.22.154.1**|b0.nic.mormon.        **518400**    IN    AAAA    2a01:8840:97:0:0:0:0:1|
|c0.nic.mormon.        **172800**    IN    **AAAA**    **2a01:8840:98:0:0:0:0:1**|c0.nic.mormon.        **518400**    IN    **AAAA**    **2a01:8840:98:0:0:0:0:1**|
||c0.nic.mormon.        **518400**    IN    **A**    **65.22.154.1**|
#
## chanel
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## dish
|expected|actual|
|--------|---|
|dish.            86400    IN    DS    **24325** **8** 2 **1D7C249775114E100DECB96C9E6CBA080BFFC5398498C6D3FE2EED6CBAA34663**|dish.            86400    IN    DS    **55986** **7** **1 3E785B9E04D1491A22BEBC270AB1E93CAD55ECF5**|
|a0.nic.dish.        **172800**    IN    A    65.22.88.33|**dish.            86400    IN    DS    55986 7 **2 **57B86C15DF0D7F00A492C56FC9D1D6C540B78C5C2EAB479711AED5381D198D4B**|
|a0.nic.dish.        **172800**    IN    AAAA    2a01:8840:56:0:0:0:0:33|a0.nic.dish.        **518400**    IN    A    65.22.88.33|
|a2.nic.dish.        **172800**    IN    **A**    **65.22.91.33**|a0.nic.dish.        **518400**    IN    AAAA    2a01:8840:56:0:0:0:0:33|
|a2.nic.dish.        **172800**    IN    **AAAA**    **2a01:8840:59:0:0:0:0:33**|a2.nic.dish.        **518400**    IN    **AAAA**    **2a01:8840:59:0:0:0:0:33**|
|b0.nic.dish.        **172800**    IN    A    65.22.89.33|a2.nic.dish.        **518400**    IN    **A**    **65.22.91.33**|
|b0.nic.dish.        **172800**    IN    AAAA    2a01:8840:57:0:0:0:0:33|b0.nic.dish.        **518400**    IN    A    65.22.89.33|
|c0.nic.dish.        **172800**    IN    A    65.22.90.33|b0.nic.dish.        **518400**    IN    AAAA    2a01:8840:57:0:0:0:0:33|
|c0.nic.dish.        **172800**    IN    AAAA    2a01:8840:58:0:0:0:0:33|c0.nic.dish.        **518400**    IN    A    65.22.90.33|
||c0.nic.dish.        **518400**    IN    AAAA    2a01:8840:58:0:0:0:0:33|
#
## nf
|expected|actual|
|--------|---|
|**nf.            172800    IN    NS    ns.cocca.fr.**||
||**nf.            172800    IN    NS    ns.cocca.fr.**|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|ns.anycast.nic.nf.    **172800**    IN    **A**    **204.61.216.51**|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|ns.anycast.nic.nf.    **172800**    IN    **AAAA**    **2001:500:14:6051:ad:0:0:1**|ns.anycast.nic.nf.    **518400**    IN    **AAAA**    **2001:500:14:6051:ad:0:0:1**|
||ns.anycast.nic.nf.    **518400**    IN    **A**    **204.61.216.51**|
#
## ni
|expected|actual|
|--------|---|
||**ni.            172800    IN    NS    dns.nic.cr.**|
||**ni.            172800    IN    NS    ns.ideay.net.ni.**|
|**ni.            172800    IN    NS    ns.ideay.net.ni.**||
|**ni.            172800    IN    NS    **dns**-ext**.nic.cr.|dns.nic.cr.        **518400**    IN    A    200.107.82.**100**|
|**dns-ext.nic.cr.**        **172800    **IN    A    200.107.82.**219**|dns.nic.cr.        **518400**    IN    AAAA    **2001:13c7:7004:1:0:0:0:d100**|
|dns**-ext**.nic.cr.        **172800**    IN    AAAA    **2001:13c7:7004:110:0:0:0:219**|ns.uu.net.        **518400**    IN    A    137.39.1.3|
|ns.uu.net.        **172800**    IN    A    137.39.1.3|ns.ideay.net.ni.    **518400**    IN    A    186.1.31.8|
|ns.ideay.net.ni.    **172800**    IN    A    186.1.31.8|ns.ni.            **518400**    IN    A    165.98.1.2|
|ns.ni.            **172800**    IN    A    165.98.1.2|ns2.ni.            **518400**    IN    A    200.9.187.2|
|ns2.ni.            **172800**    IN    A    200.9.187.2|ns3.ni.            **518400**    IN    A    190.85.232.145|
|ns3.ni.            **172800**    IN    A    190.85.232.145||
#
## weber
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bnpparibas
|expected|actual|
|--------|---|
|bnpparibas.        **86400**    IN    **DS**    **33820** **7 2 30D65921D1475578245648251C804891B97CB899D4F35E658F8BFDD8C75D9670**|**a0.nic.**bnpparibas.    **518400**    IN    **AAAA**    **2a01:8840:3e:0:0:0:0:9**|
|a0.nic.bnpparibas.    **172800**    IN    A    65.22.64.9|a0.nic.bnpparibas.    **518400**    IN    A    65.22.64.9|
|**a0**.nic.bnpparibas.    **172800**    IN    AAAA    **2a01:8840:3e:0:0:0:0:9**|**a2**.nic.bnpparibas.    **518400**    IN    AAAA    **2a01:8840:41:0:0:0:0:9**|
|a2.nic.bnpparibas.    **172800**    IN    A    65.22.67.9|a2.nic.bnpparibas.    **518400**    IN    A    65.22.67.9|
|**a2.nic.bnpparibas.    172800    IN    AAAA    2a01:8840:41:0:0:0:0:9**|b0.nic.bnpparibas.    **518400**    IN    A    65.22.65.9|
|b0.nic.bnpparibas.    **172800**    IN    A    65.22.65.9|b0.nic.bnpparibas.    **518400**    IN    AAAA    2a01:8840:3f:0:0:0:0:9|
|b0.nic.bnpparibas.    **172800**    IN    AAAA    2a01:8840:3f:0:0:0:0:9|c0.nic.bnpparibas.    **518400**    IN    A    65.22.66.9|
|c0.nic.bnpparibas.    **172800**    IN    A    65.22.66.9|c0.nic.bnpparibas.    **518400**    IN    AAAA    2a01:8840:40:0:0:0:0:9|
|c0.nic.bnpparibas.    **172800**    IN    AAAA    2a01:8840:40:0:0:0:0:9||
#
## fidelity
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## med
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## godaddy
|expected|actual|
|--------|---|
|godaddy.        86400    IN    DS    **6040** **8** 2 **9AAF85A8B827BB0E45862EA29FA0AB0C1F7B2A7CA8AC6E14966F4F267324A98C**|godaddy.        86400    IN    DS    **21655** **7** **1 FB09046631C8E4279279BF889D4A6905352D4757**|
|a0.nic.godaddy.        **172800**    IN    A    65.22.20.25|**godaddy.        86400    IN    DS    21655 7 **2 **8102F8799BC84E08910028518CCAF495B5819FDC961CCC4A9A8EAF278A5C6246**|
|a0.nic.godaddy.        **172800**    IN    AAAA    2a01:8840:16:0:0:0:0:25|a0.nic.godaddy.        **518400**    IN    A    65.22.20.25|
|a2.nic.godaddy.        **172800**    IN    **A**    **65.22.23.25**|a0.nic.godaddy.        **518400**    IN    AAAA    2a01:8840:16:0:0:0:0:25|
|a2.nic.godaddy.        **172800**    IN    **AAAA**    **2a01:8840:19:0:0:0:0:25**|a2.nic.godaddy.        **518400**    IN    **AAAA**    **2a01:8840:19:0:0:0:0:25**|
|b0.nic.godaddy.        **172800**    IN    A    65.22.21.25|a2.nic.godaddy.        **518400**    IN    **A**    **65.22.23.25**|
|b0.nic.godaddy.        **172800**    IN    AAAA    2a01:8840:17:0:0:0:0:25|b0.nic.godaddy.        **518400**    IN    A    65.22.21.25|
|c0.nic.godaddy.        **172800**    IN    **A**    **65.22.22.25**|b0.nic.godaddy.        **518400**    IN    AAAA    2a01:8840:17:0:0:0:0:25|
|c0.nic.godaddy.        **172800**    IN    **AAAA**    **2a01:8840:18:0:0:0:0:25**|c0.nic.godaddy.        **518400**    IN    **AAAA**    **2a01:8840:18:0:0:0:0:25**|
||c0.nic.godaddy.        **518400**    IN    **A**    **65.22.22.25**|
#
## nikon
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## total
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## shangrila
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## dtv
|expected|actual|
|--------|---|
|dtv.            86400    IN    DS    **51301** **8** 2 **EB39CB7D7771F169881C4B9ECE63E510C949949741D56988D8BB9CCE24EB3479**|dtv.            86400    IN    DS    **22296** **7** **1 452BEF6722ED225D3320F082AE8DE685661C101F**|
|a0.nic.dtv.        **172800**    IN    **A**    **65.22.228.1**|**dtv.            86400    IN    DS    22296 7 **2 **BF1BD7142228D1F6D621A539BDD8EB842F7D6D3E8AE2DBC9F94CBF469633C64D**|
|a0.nic.dtv.        **172800**    IN    **AAAA**    **2a01:8840:de:0:0:0:0:1**|a0.nic.dtv.        **518400**    IN    **AAAA**    **2a01:8840:de:0:0:0:0:1**|
|a2.nic.dtv.        **172800**    IN    A    65.22.231.1|a0.nic.dtv.        **518400**    IN    **A**    **65.22.228.1**|
|a2.nic.dtv.        **172800**    IN    AAAA    2a01:8840:e1:0:0:0:0:1|a2.nic.dtv.        **518400**    IN    A    65.22.231.1|
|b0.nic.dtv.        **172800**    IN    **A**    **65.22.229.1**|a2.nic.dtv.        **518400**    IN    AAAA    2a01:8840:e1:0:0:0:0:1|
|b0.nic.dtv.        **172800**    IN    **AAAA**    **2a01:8840:df:0:0:0:0:1**|b0.nic.dtv.        **518400**    IN    **AAAA**    **2a01:8840:df:0:0:0:0:1**|
|c0.nic.dtv.        **172800**    IN    A    65.22.230.1|b0.nic.dtv.        **518400**    IN    **A**    **65.22.229.1**|
|c0.nic.dtv.        **172800**    IN    AAAA    2a01:8840:e0:0:0:0:0:1|c0.nic.dtv.        **518400**    IN    A    65.22.230.1|
||c0.nic.dtv.        **518400**    IN    AAAA    2a01:8840:e0:0:0:0:0:1|
#
## xn--3pxu8k
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## srl
|expected|actual|
|--------|---|
|srl.            86400    IN    DS    **33382** **8** 2 **8414F09570E69F8FF6099EF53136AA4304A85FE21BCB1F65E937AF7C5E5133CD**|srl.            86400    IN    DS    **16923** **7** **1 D238CCACAB989CB47AD542AAB1ABA32BB601CE33**|
|a0.nic.srl.        **172800**    IN    **A**    **65.22.80.33**|**srl.            86400    IN    DS    16923 7 **2 **DDC08432E8534F2FB8E8C23CAB08263E74C7ADA5BC52C17B3C03245868690938**|
|a0.nic.srl.        **172800**    IN    **AAAA**    **2a01:8840:4e:0:0:0:0:33**|a0.nic.srl.        **518400**    IN    **AAAA**    **2a01:8840:4e:0:0:0:0:33**|
|a2.nic.srl.        **172800**    IN    A    65.22.83.33|a0.nic.srl.        **518400**    IN    **A**    **65.22.80.33**|
|a2.nic.srl.        **172800**    IN    AAAA    2a01:8840:51:0:0:0:0:33|a2.nic.srl.        **518400**    IN    A    65.22.83.33|
|b0.nic.srl.        **172800**    IN    A    65.22.81.33|a2.nic.srl.        **518400**    IN    AAAA    2a01:8840:51:0:0:0:0:33|
|b0.nic.srl.        **172800**    IN    AAAA    2a01:8840:4f:0:0:0:0:33|b0.nic.srl.        **518400**    IN    A    65.22.81.33|
|c0.nic.srl.        **172800**    IN    **A**    **65.22.82.33**|b0.nic.srl.        **518400**    IN    AAAA    2a01:8840:4f:0:0:0:0:33|
|c0.nic.srl.        **172800**    IN    **AAAA**    **2a01:8840:50:0:0:0:0:33**|c0.nic.srl.        **518400**    IN    **AAAA**    **2a01:8840:50:0:0:0:0:33**|
||c0.nic.srl.        **518400**    IN    **A**    **65.22.82.33**|
#
## orange
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## pe
|expected|actual|
|--------|---|
|**pe.            172800    IN    NS    a.lactld.org.**||
|pe1.dnsnode.net.    **172800**    IN    A    194.146.106.82|pe1.dnsnode.net.    **518400**    IN    A    194.146.106.82|
|pe1.dnsnode.net.    **172800**    IN    AAAA    2001:67c:1010:20:0:0:0:53|pe1.dnsnode.net.    **518400**    IN    AAAA    2001:67c:1010:20:0:0:0:53|
|**a.lactld.org.        172800    IN    A    200.0.68.10**|quipu.rcp.net.pe.    **518400**    IN    A    200.1.176.4|
|**a.lactld.org.        172800    IN    AAAA    2801:14:a000:0:0:0:0:10**|pch.rcp.pe.        **518400**    IN    **AAAA**    **2001:500:14:6085:ad:0:0:1**|
|quipu.rcp.net.pe.    **172800**    IN    A    200.1.176.4|pch.rcp.pe.        **518400**    IN    **A**    **204.61.216.85**|
|pch.rcp.pe.        **172800**    IN    **A**    **204.61.216.85**||
|pch.rcp.pe.        **172800**    IN    **AAAA**    **2001:500:14:6085:ad:0:0:1**||
#
## accenture
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## online
|expected|actual|
|--------|---|
|online.            172800    IN    NS    **e**.nic.online.|online.            172800    IN    NS    **c**.nic.online.|
|online.            172800    IN    NS    **f**.nic.online.|online.            172800    IN    NS    **d**.nic.online.|
|a.nic.online.        **172800**    IN    **A**    **194.169.218.54**|a.nic.online.        **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:54**|
|a.nic.online.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:54**|a.nic.online.        **518400**    IN    **A**    **194.169.218.54**|
|b.nic.online.        **172800**    IN    A    185.24.64.54|b.nic.online.        **518400**    IN    A    185.24.64.54|
|b.nic.online.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:54|b.nic.online.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:54|
|**e**.nic.online.        **172800**    IN    **A**    **212.18.248.54**|**c**.nic.online.        **518400**    IN    **AAAA**    **2a02:e180:3:0:0:0:0:7**|
|**e**.nic.online.        **172800**    IN    **AAAA**    **2a04:2b00:13ee:0:0:0:0:54**|**c**.nic.online.        **518400**    IN    **A**    **185.38.99.7**|
|**f**.nic.online.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:54**|**d**.nic.online.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:7**|
|**f**.nic.online.        **172800**    IN    A    **212**.**18**.**249**.**54**|**d**.nic.online.        **518400**    IN    A    **108**.**59**.**161**.**7**|
#
## pl
|expected|actual|
|--------|---|
|a-dns.pl.        **172800**    IN    A    194.181.87.156|a-dns.pl.        **518400**    IN    A    194.181.87.156|
|a-dns.pl.        **172800**    IN    AAAA    2001:a10:121:1:0:0:0:156|a-dns.pl.        **518400**    IN    AAAA    2001:a10:121:1:0:0:0:156|
|b-dns.pl.        **172800**    IN    **A**    **192.195.72.53**|b-dns.pl.        **518400**    IN    **AAAA**    **2001:7f9:c:0:0:0:0:53**|
|b-dns.pl.        **172800**    IN    **AAAA**    **2001:7f9:c:0:0:0:0:53**|b-dns.pl.        **518400**    IN    **A**    **192.195.72.53**|
|c-dns.pl.        **172800**    IN    A    93.190.128.146|c-dns.pl.        **518400**    IN    A    93.190.128.146|
|c-dns.pl.        **172800**    IN    AAAA    2a02:38:14:0:0:0:0:146|c-dns.pl.        **518400**    IN    AAAA    2a02:38:14:0:0:0:0:146|
|d-dns.pl.        **172800**    IN    **A**    **185.159.197.48**|d-dns.pl.        **518400**    IN    **AAAA**    **2620:10a:80aa:0:0:0:0:48**|
|d-dns.pl.        **172800**    IN    **AAAA**    **2620:10a:80aa:0:0:0:0:48**|d-dns.pl.        **518400**    IN    **A**    **185.159.197.48**|
|e-dns.pl.        **172800**    IN    A    46.28.245.82|e-dns.pl.        **518400**    IN    A    46.28.245.82|
|f-dns.pl.        **172800**    IN    A    194.0.25.29|f-dns.pl.        **518400**    IN    A    194.0.25.29|
|f-dns.pl.        **172800**    IN    AAAA    2001:678:20:0:0:0:0:29|f-dns.pl.        **518400**    IN    AAAA    2001:678:20:0:0:0:0:29|
|g-dns.pl.        **172800**    IN    **A**    **149.156.1.252**|g-dns.pl.        **518400**    IN    **AAAA**    **2001:6d8:1001:1:0:0:0:252**|
|g-dns.pl.        **172800**    IN    **AAAA**    **2001:6d8:1001:1:0:0:0:252**|g-dns.pl.        **518400**    IN    **A**    **149.156.1.252**|
|h-dns.pl.        **172800**    IN    A    185.159.198.48|h-dns.pl.        **518400**    IN    A    185.159.198.48|
|h-dns.pl.        **172800**    IN    AAAA    2620:10a:80ab:0:0:0:0:48|h-dns.pl.        **518400**    IN    AAAA    2620:10a:80ab:0:0:0:0:48|
|i-dns.pl.        **172800**    IN    A    156.154.100.15|i-dns.pl.        **518400**    IN    A    156.154.100.15|
|**i-dns.pl.        172800    IN    AAAA    2001:502:2eda:0:0:0:0:15**||
#
## pm
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|e.ext.nic.fr.        **172800**    IN    A    193.176.144.22|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|e.ext.nic.fr.        **172800**    IN    AAAA    2a00:d78:0:102:193:176:144:22|e.ext.nic.fr.        **518400**    IN    A    193.176.144.22|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|e.ext.nic.fr.        **518400**    IN    AAAA    2a00:d78:0:102:193:176:144:22|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## pn
|expected|actual|
|--------|---|
|**pn.            172800    IN    NS    ns0.pitcairn.net.pn.**||
|**pn.            172800    IN    NS    ns1.pitcairn.net.pn.**||
|fork.sth.dnsnode.net.    **172800**    IN    A    77.72.229.254|**pn.            172800    IN    NS    ns0.pitcairn.net.pn.**|
|fork.sth.dnsnode.net.    **172800**    IN    AAAA    2a01:3f0:0:306:0:0:0:53|**pn.            172800    IN    NS    ns1.pitcairn.net.pn.**|
|ns0.pitcairn.net.pn.    **172800**    IN    A    173.230.153.180|**pn.            172800    IN    NS    ns2.pitcairn.net.pn.**|
|ns1.pitcairn.net.pn.    **172800**    IN    A    204.61.216.136|fork.sth.dnsnode.net.    **518400**    IN    A    77.72.229.254|
|**ns1**.pitcairn.net.pn.    **172800**    IN    AAAA    **2001:500:14:6136:ad:0:0:1**|fork.sth.dnsnode.net.    **518400**    IN    AAAA    2a01:3f0:0:306:0:0:0:53|
|dns1.nominetdns.uk.    **172800**    IN    A    213.248.219.254|ns0.pitcairn.net.pn.    **518400**    IN    A    173.230.153.180|
|**dns1**.nominetdns.uk.    **172800**    IN    AAAA    **2a01:618:403:0:0:0:0:254**|ns1.pitcairn.net.pn.    **518400**    IN    **AAAA    2001:500:14:6136:ad:0:0:1**|
|dns4.nominetdns.uk.    **172800**    IN    A    43.230.51.254|**ns1.pitcairn.net.pn.    518400    IN    **A    204.61.216.136|
|**dns4.nominetdns.uk.    172800    IN    AAAA    2401:fd80:407:0:0:0:0:254**|**ns2**.pitcairn.net.pn.    **518400**    IN    **A    80.68.93.100**|
||**dns1.nominetdns.uk.    518400    IN    **AAAA    **2a01:618:403:0:0:0:0:254**|
||dns1.nominetdns.uk.    **518400**    IN    A    213.248.219.254|
||**dns4**.nominetdns.uk.    **518400**    IN    AAAA    **2401:fd80:407:0:0:0:0:254**|
||dns4.nominetdns.uk.    **518400**    IN    A    43.230.51.254|
#
## pr
|expected|actual|
|--------|---|
|pr.            86400    IN    DS    **5134** **8** **2** **2E7F12833596203DBEF32DBCEBC2CFD2F6D3AA4432A9BB39927394C6CF1A844A**|pr.            86400    IN    DS    **21436** **5** **1** **749B940F0D9471FF349536D22AAF36D26BBCA219**|
|pr-dns.denic.de.    **172800**    IN    A    194.0.11.111|pr-dns.denic.de.    **518400**    IN    A    194.0.11.111|
|pr-dns.denic.de.    **172800**    IN    AAAA    2001:678:e:111:0:0:0:53|pr-dns.denic.de.    **518400**    IN    AAAA    2001:678:e:111:0:0:0:53|
|a0.pr.afilias-nst.info.    **172800**    IN    A    199.254.59.17|a0.pr.afilias-nst.info.    **518400**    IN    A    199.254.59.17|
|a0.pr.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:17|a0.pr.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:17|
|a2.pr.afilias-nst.info.    **172800**    IN    **A**    **199.249.116.17**|a2.pr.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:44:0:0:0:0:17**|
|a2.pr.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:44:0:0:0:0:17**|a2.pr.afilias-nst.info.    **518400**    IN    **A**    **199.249.116.17**|
|c0.pr.afilias-nst.info.    **172800**    IN    A    199.254.61.17|c0.pr.afilias-nst.info.    **518400**    IN    A    199.254.61.17|
|c0.pr.afilias-nst.info.    **172800**    IN    AAAA    2001:500:27:0:0:0:0:17|c0.pr.afilias-nst.info.    **518400**    IN    AAAA    2001:500:27:0:0:0:0:17|
|b0.pr.afilias-nst.org.    **172800**    IN    A    199.254.60.17|b0.pr.afilias-nst.org.    **518400**    IN    **AAAA    2001:500:26:0:0:0:0:17**|
|**b0**.pr.afilias-nst.org.    **172800**    IN    AAAA    **2001:500:26:0:0:0:0:17**|**b0.pr.afilias-nst.org.    518400    IN    **A    199.254.60.17|
|b2.pr.afilias-nst.org.    **172800**    IN    A    199.249.124.17|**b2**.pr.afilias-nst.org.    **518400**    IN    AAAA    **2001:500:4c:0:0:0:0:17**|
|**b2**.pr.afilias-nst.org.    **172800**    IN    AAAA    **2001:500:4c:0:0:0:0:17**|b2.pr.afilias-nst.org.    **518400**    IN    A    199.249.124.17|
|d0.pr.afilias-nst.org.    **172800**    IN    A    199.254.62.17|**d0**.pr.afilias-nst.org.    **518400**    IN    AAAA    **2001:500:28:0:0:0:0:17**|
|**d0**.**pr**.**afilias-nst.**org.    **172800**    IN    AAAA    **2001:500:28:0:0:0:0:17**|d0.pr.afilias-nst.org.    **518400**    IN    A    199.254.62.17|
|a.lactld.org.        **172800**    IN    A    200.0.68.10|**a**.**lactld**.org.        **518400**    IN    AAAA    **2801:14:a000:0:0:0:0:10**|
|**a.lactld.org.        172800    IN    AAAA    2801:14:a000:0:0:0:0:10**|a.lactld.org.        **518400**    IN    A    200.0.68.10|
#
## pt
|expected|actual|
|--------|---|
||**pt.            172800    IN    NS    f.dns.pt.**|
|ns.dns.br.        **172800**    IN    A    200.160.0.5|ns.dns.br.        **518400**    IN    **AAAA    2001:12ff:0:a20:0:0:0:5**|
|**ns**.**dns**.**br**.        **172800**    IN    AAAA    **2001:12ff:0:a20:0:0:0:5**|**ns.dns.br.        518400    IN    **A    200.160.0.5|
|ns2.nic.fr.        **172800**    IN    A    192.93.0.4|**ns2**.**nic**.**fr**.        **518400**    IN    AAAA    **2001:660:3005:1:0:0:1:2**|
|**ns2**.**nic**.**fr**.        **172800**    IN    AAAA    **2001:660:3005:1:0:0:1:2**|ns2.nic.fr.        **518400**    IN    A    192.93.0.4|
|a.dns.pt.        **172800**    IN    A    185.39.208.1|**a**.**dns**.**pt**.        **518400**    IN    AAAA    **2a04:6d80:0:0:0:0:0:1**|
|**a.dns.pt.        172800    IN    AAAA    2a04:6d80:0:0:0:0:0:1**|a.dns.pt.        **518400**    IN    A    185.39.208.1|
|b.dns.pt.        **172800**    IN    A    194.0.25.23|b.dns.pt.        **518400**    IN    A    194.0.25.23|
|b.dns.pt.        **172800**    IN    AAAA    2001:678:20:0:0:0:0:23|b.dns.pt.        **518400**    IN    AAAA    2001:678:20:0:0:0:0:23|
|c.dns.pt.        **172800**    IN    A    204.61.216.105|c.dns.pt.        **518400**    IN    A    204.61.216.105|
|c.dns.pt.        **172800**    IN    AAAA    2001:500:14:6105:ad:0:0:1|c.dns.pt.        **518400**    IN    AAAA    2001:500:14:6105:ad:0:0:1|
|d.dns.pt.        **172800**    IN    A    185.39.210.1|d.dns.pt.        **518400**    IN    A    185.39.210.1|
|d.dns.pt.        **172800**    IN    AAAA    2a04:6d82:0:0:0:0:0:1|d.dns.pt.        **518400**    IN    AAAA    2a04:6d82:0:0:0:0:0:1|
|e.dns.pt.        **172800**    IN    A    193.136.192.64|e.dns.pt.        **518400**    IN    **AAAA    2001:690:a00:4001:0:0:0:64**|
|**e**.dns.pt.        **172800**    IN    AAAA    **2001:690:a00:4001:0:0:0:64**|**e.dns.pt.        518400    IN    **A    193.136.192.64|
|g.dns.pt.        **172800**    IN    A    193.136.2.226|**f**.dns.pt.        **518400**    IN    **A    162.88.45.1**|
|g.dns.pt.        **172800**    IN    AAAA    2001:690:a80:4001:0:0:0:100|**f.dns.pt.        518400    IN    **AAAA    **2600:2000:3009:0:0:0:0:1**|
|h.dns.pt.        **172800**    IN    A    194.146.106.138|g.dns.pt.        **518400**    IN    A    193.136.2.226|
|h.dns.pt.        **172800**    IN    AAAA    2001:67c:1010:35:0:0:0:53|g.dns.pt.        **518400**    IN    AAAA    2001:690:a80:4001:0:0:0:100|
||h.dns.pt.        **518400**    IN    A    194.146.106.138|
||h.dns.pt.        **518400**    IN    AAAA    2001:67c:1010:35:0:0:0:53|
#
## pw
|expected|actual|
|--------|---|
|**pw.            86400    IN    DS    26645 7 1 58EE332D303E2A64B7449C43AB770DAA1CA74C40**||
|**pw.            86400    IN    DS    26645 7 2 7EF397EDF4D7CA228C0F5111F5E1696CDBF279C0B6AFA48FC7E71A12E07E5880**||
|pw.            172800    IN    NS    **ns5**.nic.pw.|pw.            172800    IN    NS    **ns3**.nic.pw.|
|pw.            172800    IN    NS    **ns6**.nic.pw.|pw.            172800    IN    NS    **ns4**.nic.pw.|
|**ns1**.**nic.**pw.        **172800**    IN    **A**    **194**.**169**.**218**.**12**|**pw**.**            86400    IN    DS    26645 7 2 7EF397EDF4D7CA228C0F5111F5E1696CDBF279C0B6AFA48FC7E71A12E07E5880**|
|ns1.nic.pw.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:12**|pw.            **86400**    IN    **DS**    **26645 7 1 58EE332D303E2A64B7449C43AB770DAA1CA74C40**|
|ns2.nic.pw.        **172800**    IN    A    185.24.64.12|**ns1**.**nic**.**pw**.        **518400    IN    AAAA    2001:67c:13cc:0:0:0:1:12**|
|ns2.nic.pw.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:12|ns1.nic.pw.        **518400**    IN    **A**    **194.169.218.12**|
|**ns5**.nic.pw.        **172800**    IN    A    **212**.**18**.**248**.**12**|ns2.nic.pw.        **518400**    IN    A    185.24.64.12|
|**ns5**.nic.pw.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:12**|ns2.nic.pw.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:12|
|**ns6**.nic.pw.        **172800**    IN    A    **212**.**18**.**249**.**12**|**ns3**.nic.pw.        **518400**    IN    A    **185**.**38**.**99**.**11**|
|**ns6**.nic.pw.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:12**|**ns3**.nic.pw.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:11**|
||**ns4**.nic.pw.        **518400**    IN    A    **108**.**59**.**161**.**11**|
||**ns4**.nic.pw.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:11**|
#
## delta
|expected|actual|
|--------|---|
|**delta.            86400    IN    DS    58345 7 2 0C04A3BBBAC7A82AF8BA977490B01E8BA895F666D9B40295427B5A44424EE925**||
|a0.nic.delta.        **172800**    IN    A    65.22.224.25|a0.nic.delta.        **518400**    IN    **AAAA    2a01:8840:da:0:0:0:0:25**|
|**a0**.nic.delta.        **172800**    IN    AAAA    **2a01:8840:da:0:0:0:0:25**|**a0.nic.delta.        518400    IN    **A    65.22.224.25|
|a2.nic.delta.        **172800**    IN    A    65.22.227.25|**a2**.nic.delta.        **518400**    IN    AAAA    **2a01:8840:dd:0:0:0:0:25**|
|**a2.nic.delta.        172800    IN    AAAA    2a01:8840:dd:0:0:0:0:25**|a2.nic.delta.        **518400**    IN    A    65.22.227.25|
|b0.nic.delta.        **172800**    IN    A    65.22.225.25|b0.nic.delta.        **518400**    IN    A    65.22.225.25|
|b0.nic.delta.        **172800**    IN    AAAA    2a01:8840:db:0:0:0:0:25|b0.nic.delta.        **518400**    IN    AAAA    2a01:8840:db:0:0:0:0:25|
|c0.nic.delta.        **172800**    IN    **A**    **65.22.226.25**|c0.nic.delta.        **518400**    IN    **AAAA**    **2a01:8840:dc:0:0:0:0:25**|
|c0.nic.delta.        **172800**    IN    **AAAA**    **2a01:8840:dc:0:0:0:0:25**|c0.nic.delta.        **518400**    IN    **A**    **65.22.226.25**|
#
## blockbuster
|expected|actual|
|--------|---|
|blockbuster.        86400    IN    DS    **20059** **8** 2 **7CC46EE5DB147183B41BDA17AC3A5CE97963064F139E80A7C2B60AA8BD5200E7**|blockbuster.        86400    IN    DS    **30318** **7** **1 5FA090D590D9D15EF82916100F70F967C5240366**|
|a0.nic.blockbuster.    **172800**    IN    A    65.22.92.25|**blockbuster.        86400    IN    DS    30318 7 **2 **4F6038260EE31DA7E62A7165052091029399AF4DA8B44BA13BF972DFC6D97A13**|
|a0.nic.blockbuster.    **172800**    IN    AAAA    2a01:8840:5a:0:0:0:0:25|a0.nic.blockbuster.    **518400**    IN    A    65.22.92.25|
|a2.nic.blockbuster.    **172800**    IN    **A**    **65.22.95.25**|a0.nic.blockbuster.    **518400**    IN    AAAA    2a01:8840:5a:0:0:0:0:25|
|a2.nic.blockbuster.    **172800**    IN    **AAAA**    **2a01:8840:5d:0:0:0:0:25**|a2.nic.blockbuster.    **518400**    IN    **AAAA**    **2a01:8840:5d:0:0:0:0:25**|
|b0.nic.blockbuster.    **172800**    IN    A    65.22.93.25|a2.nic.blockbuster.    **518400**    IN    **A**    **65.22.95.25**|
|b0.nic.blockbuster.    **172800**    IN    AAAA    2a01:8840:5b:0:0:0:0:25|b0.nic.blockbuster.    **518400**    IN    A    65.22.93.25|
|c0.nic.blockbuster.    **172800**    IN    **A**    **65.22.94.25**|b0.nic.blockbuster.    **518400**    IN    AAAA    2a01:8840:5b:0:0:0:0:25|
|c0.nic.blockbuster.    **172800**    IN    **AAAA**    **2a01:8840:5c:0:0:0:0:25**|c0.nic.blockbuster.    **518400**    IN    **AAAA**    **2a01:8840:5c:0:0:0:0:25**|
||c0.nic.blockbuster.    **518400**    IN    **A**    **65.22.94.25**|
#
## vlaanderen
|expected|actual|
|--------|---|
||**vlaanderen.        86400    IN    DS    9286 8 1 D8689711ACE25FB8C7DFBD54443BF90411A75C57**|
|**c**.**ns.dns.be.**        **172800**    IN    **A**    **194.0.43.**1|**vlaanderen**.        **86400**    IN    **DS**    **54397 8 **1 **00689FA2394B6E5D080887DF8C162368B362D855**|
|c.ns.dns.be.        **172800**    IN    AAAA    2001:678:68:0:0:0:0:1|c.ns.dns.be.        **518400**    IN    AAAA    2001:678:68:0:0:0:0:1|
|**d**.ns.dns.be.        **172800**    IN    A    194.0.**44**.1|**c**.ns.dns.be.        **518400**    IN    A    194.0.**43**.1|
|d.ns.dns.be.        **172800**    IN    AAAA    2001:678:6c:0:0:0:0:1|d.ns.dns.be.        **518400**    IN    AAAA    2001:678:6c:0:0:0:0:1|
|y.ns.dns.be.        **172800**    IN    A    120.29.253.8|**d.ns.dns.be.        518400    IN    A    194.0.44.1**|
|y.ns.dns.be.        **172800**    IN    AAAA    2001:dcd:7:0:0:0:0:8|y.ns.dns.be.        **518400**    IN    A    120.29.253.8|
|a.nic.vlaanderen.    **172800**    IN    A    194.0.6.1|y.ns.dns.be.        **518400**    IN    AAAA    2001:dcd:7:0:0:0:0:8|
|a.nic.vlaanderen.    **172800**    IN    AAAA    2001:678:9:0:0:0:0:1|a.nic.vlaanderen.    **518400**    IN    A    194.0.6.1|
|b.nic.vlaanderen.    **172800**    IN    **A**    **194.0.37.1**|a.nic.vlaanderen.    **518400**    IN    AAAA    2001:678:9:0:0:0:0:1|
|b.nic.vlaanderen.    **172800**    IN    **AAAA**    **2001:678:64:0:0:0:0:1**|b.nic.vlaanderen.    **518400**    IN    **AAAA**    **2001:678:64:0:0:0:0:1**|
|z.nsset.vlaanderen.    **172800**    IN    A    194.0.25.19|b.nic.vlaanderen.    **518400**    IN    **A**    **194.0.37.1**|
|z.nsset.vlaanderen.    **172800**    IN    AAAA    2001:678:20:0:0:0:0:19|z.nsset.vlaanderen.    **518400**    IN    A    194.0.25.19|
||z.nsset.vlaanderen.    **518400**    IN    AAAA    2001:678:20:0:0:0:0:19|
#
## qa
|expected|actual|
|--------|---|
|a.registry.qa.        **172800**    IN    A    178.23.16.104|a.registry.qa.        **518400**    IN    A    178.23.16.104|
|b.registry.qa.        **172800**    IN    A    178.23.17.104|b.registry.qa.        **518400**    IN    A    178.23.17.104|
|c.registry.qa.        **172800**    IN    A    212.77.192.10|c.registry.qa.        **518400**    IN    A    212.77.192.10|
|d.registry.qa.        **172800**    IN    A    212.77.192.13|d.registry.qa.        **518400**    IN    A    212.77.192.13|
|e.registry.qa.        **172800**    IN    A    178.23.20.60|e.registry.qa.        **518400**    IN    A    178.23.20.60|
|f.registry.qa.        **172800**    IN    **A**    **37.209.192.6**|f.registry.qa.        **518400**    IN    **AAAA**    **2001:dcd:1:0:0:0:0:6**|
|f.registry.qa.        **172800**    IN    **AAAA**    **2001:dcd:1:0:0:0:0:6**|f.registry.qa.        **518400**    IN    **A**    **37.209.192.6**|
|g.registry.qa.        **172800**    IN    A    37.209.194.6|g.registry.qa.        **518400**    IN    A    37.209.194.6|
|g.registry.qa.        **172800**    IN    AAAA    2001:dcd:2:0:0:0:0:6|g.registry.qa.        **518400**    IN    AAAA    2001:dcd:2:0:0:0:0:6|
|h.registry.qa.        **172800**    IN    A    178.23.22.60|h.registry.qa.        **518400**    IN    A    178.23.22.60|
|**h**.registry.qa.        **172800**    IN    AAAA    **2a0c:a640:1:22:0:0:0:60**|**i**.registry.qa.        **518400**    IN    AAAA    **2001:500:14:6062:ad:0:0:1**|
|i.registry.qa.        **172800**    IN    A    204.61.216.62|i.registry.qa.        **518400**    IN    A    204.61.216.62|
|**i.registry.qa.        172800    IN    AAAA    2001:500:14:6062:ad:0:0:1**||
#
## lipsy
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## volkswagen
|expected|actual|
|--------|---|
|**volkswagen.        86400    IN    DS    16968 7 2 AF94BA077A5E70B4F0DFD984A913608CFB30E26BB885F1AFA2D55AFD15476CD5**|a0.nic.volkswagen.    **518400**    IN    A    65.22.208.25|
|a0.nic.volkswagen.    **172800**    IN    A    65.22.208.25|a0.nic.volkswagen.    **518400**    IN    AAAA    2a01:8840:ca:0:0:0:0:25|
|a0.nic.volkswagen.    **172800**    IN    AAAA    2a01:8840:ca:0:0:0:0:25|a2.nic.volkswagen.    **518400**    IN    A    65.22.211.25|
|a2.nic.volkswagen.    **172800**    IN    A    65.22.211.25|a2.nic.volkswagen.    **518400**    IN    AAAA    2a01:8840:cd:0:0:0:0:25|
|a2.nic.volkswagen.    **172800**    IN    AAAA    2a01:8840:cd:0:0:0:0:25|b0.nic.volkswagen.    **518400**    IN    **AAAA**    **2a01:8840:cb:0:0:0:0:25**|
|b0.nic.volkswagen.    **172800**    IN    **A**    **65.22.209.25**|b0.nic.volkswagen.    **518400**    IN    **A**    **65.22.209.25**|
|b0.nic.volkswagen.    **172800**    IN    **AAAA**    **2a01:8840:cb:0:0:0:0:25**|c0.nic.volkswagen.    **518400**    IN    A    65.22.210.25|
|c0.nic.volkswagen.    **172800**    IN    A    65.22.210.25|c0.nic.volkswagen.    **518400**    IN    AAAA    2a01:8840:cc:0:0:0:0:25|
|c0.nic.volkswagen.    **172800**    IN    AAAA    2a01:8840:cc:0:0:0:0:25||
#
## dvr
|expected|actual|
|--------|---|
|dvr.            86400    IN    DS    **28879** **8** 2 **FE84D723DC95EEEE237ED7452871DA942FC883F0154CDEAD6BCFA3A36EF52DC9**|dvr.            86400    IN    DS    **16495** **7** **1 B4A9CBA07A2D53143A6D6D96A750427EE0F0F333**|
|a0.nic.dvr.        **172800**    IN    **A**    **65.22.108.17**|**dvr.            86400    IN    DS    16495 7 **2 **4FF81958BD69007C911AEA73330DDF07AA2F8C1A1EF462D222ECFDA3FC0ECAE5**|
|a0.nic.dvr.        **172800**    IN    **AAAA**    **2a01:8840:6a:0:0:0:0:17**|a0.nic.dvr.        **518400**    IN    **AAAA**    **2a01:8840:6a:0:0:0:0:17**|
|a2.nic.dvr.        **172800**    IN    A    65.22.111.17|a0.nic.dvr.        **518400**    IN    **A**    **65.22.108.17**|
|a2.nic.dvr.        **172800**    IN    AAAA    2a01:8840:6d:0:0:0:0:17|a2.nic.dvr.        **518400**    IN    A    65.22.111.17|
|b0.nic.dvr.        **172800**    IN    **A**    **65.22.109.17**|a2.nic.dvr.        **518400**    IN    AAAA    2a01:8840:6d:0:0:0:0:17|
|b0.nic.dvr.        **172800**    IN    **AAAA**    **2a01:8840:6b:0:0:0:0:17**|b0.nic.dvr.        **518400**    IN    **AAAA**    **2a01:8840:6b:0:0:0:0:17**|
|c0.nic.dvr.        **172800**    IN    A    65.22.110.17|b0.nic.dvr.        **518400**    IN    **A**    **65.22.109.17**|
|c0.nic.dvr.        **172800**    IN    AAAA    2a01:8840:6c:0:0:0:0:17|c0.nic.dvr.        **518400**    IN    A    65.22.110.17|
||c0.nic.dvr.        **518400**    IN    AAAA    2a01:8840:6c:0:0:0:0:17|
#
## rexroth
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## re
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|e.ext.nic.fr.        **172800**    IN    A    193.176.144.22|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|e.ext.nic.fr.        **172800**    IN    AAAA    2a00:d78:0:102:193:176:144:22|e.ext.nic.fr.        **518400**    IN    A    193.176.144.22|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|e.ext.nic.fr.        **518400**    IN    AAAA    2a00:d78:0:102:193:176:144:22|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## homedepot
|expected|actual|
|--------|---|
|homedepot.        86400    IN    DS    **41296** **8** 2 **547D577CB0C59BC0FDCA6D4A26AB5FA73588F9F7BA554A6ADFFF6B31BA056E45**|homedepot.        86400    IN    DS    **54618** **7** **1 B78A4F2BA895067DE033F3DDBC154FA0AA002DA0**|
|a0.nic.homedepot.    **172800**    IN    A    65.22.192.1|**homedepot.        86400    IN    DS    54618 7 **2 **0A490197F5193D09B6D7E63C3FE8415B98F43B3453BC954A29BB927FD6B05CE5**|
|a0.nic.homedepot.    **172800**    IN    AAAA    2a01:8840:ba:0:0:0:0:1|a0.nic.homedepot.    **518400**    IN    A    65.22.192.1|
|a2.nic.homedepot.    **172800**    IN    **A**    **65.22.195.1**|a0.nic.homedepot.    **518400**    IN    AAAA    2a01:8840:ba:0:0:0:0:1|
|a2.nic.homedepot.    **172800**    IN    **AAAA**    **2a01:8840:bd:0:0:0:0:1**|a2.nic.homedepot.    **518400**    IN    **AAAA**    **2a01:8840:bd:0:0:0:0:1**|
|b0.nic.homedepot.    **172800**    IN    A    65.22.193.1|a2.nic.homedepot.    **518400**    IN    **A**    **65.22.195.1**|
|b0.nic.homedepot.    **172800**    IN    AAAA    2a01:8840:bb:0:0:0:0:1|b0.nic.homedepot.    **518400**    IN    A    65.22.193.1|
|c0.nic.homedepot.    **172800**    IN    **A**    **65.22.194.1**|b0.nic.homedepot.    **518400**    IN    AAAA    2a01:8840:bb:0:0:0:0:1|
|c0.nic.homedepot.    **172800**    IN    **AAAA**    **2a01:8840:bc:0:0:0:0:1**|c0.nic.homedepot.    **518400**    IN    **AAAA**    **2a01:8840:bc:0:0:0:0:1**|
||c0.nic.homedepot.    **518400**    IN    **A**    **65.22.194.1**|
#
## global
|expected|actual|
|--------|---|
|**global.            86400    IN    DS    40836 7 2 C628343FF4C09ED3DCE0A6D91F7DE3AF573F7BD872AC6FCDC7E7B422BCEDED06**||
|a0.nic.global.        **172800**    IN    A    65.22.80.1|a0.nic.global.        **518400**    IN    A    65.22.80.1|
|a0.nic.global.        **172800**    IN    AAAA    2a01:8840:4e:0:0:0:0:1|a0.nic.global.        **518400**    IN    AAAA    2a01:8840:4e:0:0:0:0:1|
|a2.nic.global.        **172800**    IN    **A**    **65.22.83.1**|a2.nic.global.        **518400**    IN    **AAAA**    **2a01:8840:51:0:0:0:0:1**|
|a2.nic.global.        **172800**    IN    **AAAA**    **2a01:8840:51:0:0:0:0:1**|a2.nic.global.        **518400**    IN    **A**    **65.22.83.1**|
|b0.nic.global.        **172800**    IN    A    65.22.81.1|b0.nic.global.        **518400**    IN    A    65.22.81.1|
|b0.nic.global.        **172800**    IN    AAAA    2a01:8840:4f:0:0:0:0:1|b0.nic.global.        **518400**    IN    AAAA    2a01:8840:4f:0:0:0:0:1|
|c0.nic.global.        **172800**    IN    A    65.22.82.1|c0.nic.global.        **518400**    IN    A    65.22.82.1|
|c0.nic.global.        **172800**    IN    AAAA    2a01:8840:50:0:0:0:0:1|c0.nic.global.        **518400**    IN    AAAA    2a01:8840:50:0:0:0:0:1|
#
## sb
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|pch.nic.sb.        **172800**    IN    A    204.61.216.31|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|pch.nic.sb.        **172800**    IN    AAAA    2001:500:14:6031:ad:0:0:1|pch.nic.sb.        **518400**    IN    A    204.61.216.31|
||pch.nic.sb.        **518400**    IN    AAAA    2001:500:14:6031:ad:0:0:1|
#
## sc
|expected|actual|
|--------|---|
|**sc.            86400    IN    DS    2539 8 2 8293FA3AC08BE770A400DDE4F250DC6BF1046F34430BE12E65C15BF2F482B26C**||
|a0.cctld.afilias-nst.info.    **172800**    IN    A    199.254.59.1|**sc.            86400    IN    DS    32953 7 1 2989C1B61462537A50928B77A85E2AD373C50B66**|
|a0.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:25:0:0:0:0:1|**sc.            86400    IN    DS    32953 7 2 E85C14114B092BF9D0B21C804CA878618BEE750ED714092180D59A2001C3708C**|
|a2.cctld.afilias-nst.info.    **172800**    IN    A    199.249.116.1|a0.cctld.afilias-nst.info.    **518400**    IN    A    199.254.59.1|
|a2.cctld.afilias-nst.info.    **172800**    IN    AAAA    2001:500:44:0:0:0:0:1|a0.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:25:0:0:0:0:1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **A**    **199.254.61.1**|a2.cctld.afilias-nst.info.    **518400**    IN    A    199.249.116.1|
|c0.cctld.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|a2.cctld.afilias-nst.info.    **518400**    IN    AAAA    2001:500:44:0:0:0:0:1|
|b0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.60.1|c0.cctld.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:27:0:0:0:0:1**|
|b0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:26:0:0:0:0:1|c0.cctld.afilias-nst.info.    **518400**    IN    **A**    **199.254.61.1**|
|b2.cctld.afilias-nst.org.    **172800**    IN    A    199.249.124.1|b0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.60.1|
|b2.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:4c:0:0:0:0:1|b0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:26:0:0:0:0:1|
|d0.cctld.afilias-nst.org.    **172800**    IN    A    199.254.62.1|b2.cctld.afilias-nst.org.    **518400**    IN    A    199.249.124.1|
|d0.cctld.afilias-nst.org.    **172800**    IN    AAAA    2001:500:28:0:0:0:0:1|b2.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:4c:0:0:0:0:1|
|ns1.nic.sc.        **172800**    IN    A    41.86.57.54|d0.cctld.afilias-nst.org.    **518400**    IN    A    199.254.62.1|
||d0.cctld.afilias-nst.org.    **518400**    IN    AAAA    2001:500:28:0:0:0:0:1|
||ns1.nic.sc.        **518400**    IN    A    41.86.57.54|
#
## mil
|expected|actual|
|--------|---|
|mil.            86400    IN    DS    **51349** 8 1 **D28D15ADD021869A0A19F6CE162F55A596310FFF**|mil.            86400    IN    DS    **7765** 8 1 **D8BCC5D307AC70652F7CD21653322746EFCEA3DC**|
|mil.            86400    IN    DS    **51349** 8 2 **F4246898E30E7182322B5668847A033D78AC9B1DDA168CB431BC4CB03E9BAFBB**|mil.            86400    IN    DS    **7765** 8 2 **49E8705D169873922E701EE46D3063CD1B7C5EADC714815241C54E4399B9BF09**|
|con1.nipr.mil.        **172800**    IN    A    199.252.157.234|con1.nipr.mil.        **518400**    IN    A    199.252.157.234|
|con2.nipr.mil.        **172800**    IN    A    199.252.162.234|con2.nipr.mil.        **518400**    IN    A    199.252.162.234|
|eur1.nipr.mil.        **172800**    IN    A    199.252.154.234|eur1.nipr.mil.        **518400**    IN    A    199.252.154.234|
|eur2.nipr.mil.        **172800**    IN    A    199.252.143.234|eur2.nipr.mil.        **518400**    IN    A    199.252.143.234|
|pac1.nipr.mil.        **172800**    IN    A    199.252.180.234|pac1.nipr.mil.        **518400**    IN    A    199.252.180.234|
|pac2.nipr.mil.        **172800**    IN    A    199.252.155.234|pac2.nipr.mil.        **518400**    IN    A    199.252.155.234|
#
## sh
|expected|actual|
|--------|---|
||**sh.            86400    IN    DS    55297 8 1 59E1077EFCF663D4E2B3DB25A170C735786793EF**|
|a0.nic.sh.        **172800**    IN    **A**    **65.22.160.9**|a0.nic.sh.        **518400**    IN    **AAAA**    **2a01:8840:9e:0:0:0:0:9**|
|a0.nic.sh.        **172800**    IN    **AAAA**    **2a01:8840:9e:0:0:0:0:9**|a0.nic.sh.        **518400**    IN    **A**    **65.22.160.9**|
|a2.nic.sh.        **172800**    IN    A    65.22.163.9|a2.nic.sh.        **518400**    IN    A    65.22.163.9|
|a2.nic.sh.        **172800**    IN    AAAA    2a01:8840:a1:0:0:0:0:9|a2.nic.sh.        **518400**    IN    AAAA    2a01:8840:a1:0:0:0:0:9|
|b0.nic.sh.        **172800**    IN    **A**    **65.22.161.9**|b0.nic.sh.        **518400**    IN    **AAAA**    **2a01:8840:9f:0:0:0:0:9**|
|b0.nic.sh.        **172800**    IN    **AAAA**    **2a01:8840:9f:0:0:0:0:9**|b0.nic.sh.        **518400**    IN    **A**    **65.22.161.9**|
|c0.nic.sh.        **172800**    IN    A    65.22.162.9|c0.nic.sh.        **518400**    IN    A    65.22.162.9|
|c0.nic.sh.        **172800**    IN    AAAA    2a01:8840:a0:0:0:0:0:9|c0.nic.sh.        **518400**    IN    AAAA    2a01:8840:a0:0:0:0:0:9|
#
## george
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## mit
|expected|actual|
|--------|---|
|mit.            86400    IN    DS    **65212** **8** 2 **321542533579CA11F6FC95AC23ABAE16A4DD112EB3785E98C51A47F5B25D2B9D**|mit.            86400    IN    DS    **50788** **7** **1 EF402CD4095664733ED65CE7096E3AB4506C675A**|
|a0.nic.mit.        **172800**    IN    A    65.22.236.17|**mit.            86400    IN    DS    50788 7 **2 **8273B0266C626C81143FF0A71EC39A8D580830C9D7B3D8B7AEF4B84AB60567A6**|
|a0.nic.mit.        **172800**    IN    AAAA    2a01:8840:e6:0:0:0:0:17|a0.nic.mit.        **518400**    IN    A    65.22.236.17|
|a2.nic.mit.        **172800**    IN    A    65.22.239.17|a0.nic.mit.        **518400**    IN    AAAA    2a01:8840:e6:0:0:0:0:17|
|a2.nic.mit.        **172800**    IN    AAAA    2a01:8840:e9:0:0:0:0:17|a2.nic.mit.        **518400**    IN    A    65.22.239.17|
|b0.nic.mit.        **172800**    IN    A    65.22.237.17|a2.nic.mit.        **518400**    IN    AAAA    2a01:8840:e9:0:0:0:0:17|
|b0.nic.mit.        **172800**    IN    AAAA    2a01:8840:e7:0:0:0:0:17|b0.nic.mit.        **518400**    IN    A    65.22.237.17|
|c0.nic.mit.        **172800**    IN    A    65.22.238.17|b0.nic.mit.        **518400**    IN    AAAA    2a01:8840:e7:0:0:0:0:17|
|c0.nic.mit.        **172800**    IN    AAAA    2a01:8840:e8:0:0:0:0:17|c0.nic.mit.        **518400**    IN    A    65.22.238.17|
||c0.nic.mit.        **518400**    IN    AAAA    2a01:8840:e8:0:0:0:0:17|
#
## origins
|expected|actual|
|--------|---|
|origins.        86400    IN    DS    **25234** **8** 2 **5290155E291FBA766EB200F5E95AC883BABFBBFDA64F5AD243068C7C8DC6019B**|origins.        86400    IN    DS    **35613** **7** **1 7064997CBE4476BE22DC96A4444B96827622A570**|
|a0.nic.origins.        **172800**    IN    A    65.22.52.33|**origins.        86400    IN    DS    35613 7 **2 **E0EDB0C263046A70AB69C3BA5C97F1DB1DF87AA78CF8D9CB83827E0F2921EBA4**|
|a0.nic.origins.        **172800**    IN    AAAA    2a01:8840:32:0:0:0:0:33|a0.nic.origins.        **518400**    IN    A    65.22.52.33|
|a2.nic.origins.        **172800**    IN    A    65.22.55.33|a0.nic.origins.        **518400**    IN    AAAA    2a01:8840:32:0:0:0:0:33|
|**a2**.nic.origins.        **172800**    IN    AAAA    **2a01:8840:35:0:0:0:0:33**|a2.nic.origins.        **518400**    IN    **AAAA    2a01:8840:35:0:0:0:0:33**|
|b0.nic.origins.        **172800**    IN    A    65.22.53.33|**a2.nic.origins.        518400    IN    **A    65.22.55.33|
|**b0**.nic.origins.        **172800**    IN    AAAA    **2a01:8840:33:0:0:0:0:33**|**b0**.nic.origins.        **518400**    IN    AAAA    **2a01:8840:33:0:0:0:0:33**|
|c0.nic.origins.        **172800**    IN    A    65.22.54.33|b0.nic.origins.        **518400**    IN    A    65.22.53.33|
|**c0.nic.origins.        172800    IN    AAAA    2a01:8840:34:0:0:0:0:33**|**c0**.nic.origins.        **518400**    IN    AAAA    **2a01:8840:34:0:0:0:0:33**|
||c0.nic.origins.        **518400**    IN    A    65.22.54.33|
#
## lamer
|expected|actual|
|--------|---|
|lamer.            86400    IN    DS    **59092** **8** 2 **F92E0E3F77B71FC4D1D69D18D013EEDCEF963C1C889B7DD1CFCE17A7E4E5B1C8**|lamer.            86400    IN    DS    **24966** **7** **1 DBA5BEC22529691B6FC271C7722B4572BA5777A9**|
|a0.nic.lamer.        **172800**    IN    A    65.22.52.25|**lamer.            86400    IN    DS    24966 7 **2 **26882F121F1AFBC725D7521AB2BFEC09F7C5D9B15DF1425250E305B9AD1F167E**|
|a0.nic.lamer.        **172800**    IN    AAAA    2a01:8840:32:0:0:0:0:25|a0.nic.lamer.        **518400**    IN    A    65.22.52.25|
|a2.nic.lamer.        **172800**    IN    A    65.22.55.25|a0.nic.lamer.        **518400**    IN    AAAA    2a01:8840:32:0:0:0:0:25|
|a2.nic.lamer.        **172800**    IN    AAAA    2a01:8840:35:0:0:0:0:25|a2.nic.lamer.        **518400**    IN    A    65.22.55.25|
|b0.nic.lamer.        **172800**    IN    A    65.22.53.25|a2.nic.lamer.        **518400**    IN    AAAA    2a01:8840:35:0:0:0:0:25|
|b0.nic.lamer.        **172800**    IN    AAAA    2a01:8840:33:0:0:0:0:25|b0.nic.lamer.        **518400**    IN    A    65.22.53.25|
|c0.nic.lamer.        **172800**    IN    A    65.22.54.25|b0.nic.lamer.        **518400**    IN    AAAA    2a01:8840:33:0:0:0:0:25|
|c0.nic.lamer.        **172800**    IN    AAAA    2a01:8840:34:0:0:0:0:25|c0.nic.lamer.        **518400**    IN    A    65.22.54.25|
||c0.nic.lamer.        **518400**    IN    AAAA    2a01:8840:34:0:0:0:0:25|
#
## ss
|expected|actual|
|--------|---|
||**ss.            172800    IN    NS    ns-ss.afrinic.net.**|
|**ss.            172800    IN    NS    ns-ss.afrinic.net.**||
|ssnic.anycastdns.cz.    **172800**    IN    A    185.28.194.194|ssnic.anycastdns.cz.    **518400**    IN    A    185.28.194.194|
|ssnic.anycastdns.cz.    **172800**    IN    A    185.38.108.108|ssnic.anycastdns.cz.    **518400**    IN    A    185.38.108.108|
|ns-ss.afrinic.net.    **172800**    IN    A    196.216.168.27|ns-ss.afrinic.net.    **518400**    IN    A    196.216.168.27|
|ns-ss.afrinic.net.    **172800**    IN    AAAA    2001:43f8:120:0:0:0:0:27|ns-ss.afrinic.net.    **518400**    IN    AAAA    2001:43f8:120:0:0:0:0:27|
|pch.nic.ss.        **172800**    IN    **A    204.61.216.130**|pch.nic.ss.        **518400**    IN    AAAA    2001:500:14:6130:ad:0:0:1|
|**pch.nic.ss.        172800    IN    **AAAA    2001:500:14:6130:ad:0:0:1|**pch**.nic.ss.        **518400**    IN    A    **204**.**61**.**216**.**130**|
|**root**.nic.ss.        **172800**    IN    A    **185**.**17**.**236**.**20**|root.nic.ss.        **518400**    IN    **A**    **196.1.4.230**|
|root.nic.ss.        **172800**    IN    **AAAA**    **2a03:dd40:3:0:0:0:0:20**|b.ns.tznic.or.tz.    **518400**    IN    A    196.216.162.70|
|b.ns.tznic.or.tz.    **172800**    IN    A    196.216.162.70|b.ns.tznic.or.tz.    **518400**    IN    AAAA    2001:43f8:e0:1:0:0:0:70|
|b.ns.tznic.or.tz.    **172800**    IN    AAAA    2001:43f8:e0:1:0:0:0:70||
#
## realestate
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sv
|expected|actual|
|--------|---|
|**sv.            172800    IN    NS    ns.uu.net.**||
|**sv.            172800    IN    NS    ns.dns.br.**||
|**sv.            172800    IN    NS    sv.cctld.authdns.ripe.net.**||
|**sv.            172800    IN    NS    cir.red.sv.**||
|**sv.            172800    IN    NS    sir.red.sv.**||
||**sv.            172800    IN    NS    cir.red.sv.**|
|ns.dns.br.        172800    IN    **A**    **200**.**160**.**0**.**5**|**sv.            172800    IN    NS    dns.nic.cr.**|
|ns.dns.br.        **172800**    IN    AAAA    2001:12ff:0:a20:0:0:0:5|**sv.            172800    IN    NS    **ns.dns.br.|
|dns**-ext**.nic.cr.        **172800**    IN    A    200.107.82.**219**|**sv.            **172800    IN    **NS**    **ns**.**uu**.**net**.|
|dns-ext.nic.cr.        **172800**    IN    AAAA    2001:13c7:7004:110:0:0:0:219|**sv.            172800    IN    NS    sir.red.sv.**|
|sv.cctld.authdns.ripe.net.    **172800**    IN    **A**    **193.0.9.112**|**sv.            172800    IN    NS    sv.cctld.authdns.ripe.net.**|
|sv.cctld.authdns.ripe.net.    **172800**    IN    **AAAA**    **2001:67c:e0:0:0:0:0:112**|ns.dns.br.        **518400**    IN    AAAA    2001:12ff:0:a20:0:0:0:5|
|ns.uu.net.        **172800**    IN    A    137.39.1.3|**ns.**dns.**br.        518400    IN    A    200.160.0.5**|
|auth02.ns.uu.net.    **172800**    IN    A    198.6.1.82|**dns.**nic.cr.        **518400**    IN    A    200.107.82.**100**|
|a.lactld.org.        **172800**    IN    **A**    **200.0.68.10**|dns**.nic.cr.        518400    IN    AAAA    2001:13c7:7004:1:0:0:0:d100**|
|a.lactld.org.        **172800**    IN    **AAAA**    **2801:14:a000:0:0:0:0:10**|**dns**-ext.nic.cr.        **518400**    IN    AAAA    2001:13c7:7004:110:0:0:0:219|
|cir.red.sv.        **172800**    IN    A    168.243.254.1|**dns-ext.nic.cr.        518400    IN    A    200.107.82.219**|
|sir.red.sv.        **172800**    IN    A    131.100.140.162|sv.cctld.authdns.ripe.net.    **518400**    IN    **AAAA**    **2001:67c:e0:0:0:0:0:112**|
||sv.cctld.authdns.ripe.net.    **518400**    IN    **A**    **193.0.9.112**|
||ns.uu.net.        **518400**    IN    A    137.39.1.3|
||auth02.ns.uu.net.    **518400**    IN    A    198.6.1.82|
||a.lactld.org.        **518400**    IN    **AAAA**    **2801:14:a000:0:0:0:0:10**|
||a.lactld.org.        **518400**    IN    **A**    **200.0.68.10**|
||cir.red.sv.        **518400**    IN    A    168.243.254.1|
||sir.red.sv.        **518400**    IN    A    131.100.140.162|
#
## star
|expected|actual|
|--------|---|
|star.            86400    IN    DS    **59872** **8** 2 **306C152BC34676BF135928882FC21C5702BF37C893F71D4DF51E3A84AD6B62E1**|star.            86400    IN    DS    **63705** **7** **1 15A46255A52218B210C6C044799520AEB5955FA4**|
|a0.nic.star.        **172800**    IN    **A**    **65.22.56.9**|**star.            86400    IN    DS    63705 7 **2 **8A381553286116582D49543EF63DE331232C9EA602F45D879FEAADBCF622CFEE**|
|a0.nic.star.        **172800**    IN    **AAAA**    **2a01:8840:36:0:0:0:0:9**|a0.nic.star.        **518400**    IN    **AAAA**    **2a01:8840:36:0:0:0:0:9**|
|a2.nic.star.        **172800**    IN    A    65.22.59.9|a0.nic.star.        **518400**    IN    **A**    **65.22.56.9**|
|a2.nic.star.        **172800**    IN    AAAA    2a01:8840:39:0:0:0:0:9|a2.nic.star.        **518400**    IN    A    65.22.59.9|
|b0.nic.star.        **172800**    IN    A    65.22.57.9|a2.nic.star.        **518400**    IN    AAAA    2a01:8840:39:0:0:0:0:9|
|b0.nic.star.        **172800**    IN    AAAA    2a01:8840:37:0:0:0:0:9|b0.nic.star.        **518400**    IN    A    65.22.57.9|
|c0.nic.star.        **172800**    IN    A    65.22.58.9|b0.nic.star.        **518400**    IN    AAAA    2a01:8840:37:0:0:0:0:9|
|c0.nic.star.        **172800**    IN    AAAA    2a01:8840:38:0:0:0:0:9|c0.nic.star.        **518400**    IN    A    65.22.58.9|
||c0.nic.star.        **518400**    IN    AAAA    2a01:8840:38:0:0:0:0:9|
#
## xn--3bst00m
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## ong
|expected|actual|
|--------|---|
|ong.            86400    IN    DS    **45685** **8** 2 **535CBA6CFB082FFCCE6584C2958DCBDF706A21DE784096A2738B3ACD8D643032**|ong.            86400    IN    DS    **48366** **7** **1 AC3A8C7FDCEB9F596A87A7DA53BB9C97B5A02F8B**|
|a0.nic.ong.        **172800**    IN    **A**    **199.19.56.1**|**ong.            86400    IN    DS    48366 7 **2 **57513E7F090220DB009BB7E1B2797BB410A8EF80C280B6FB263E8C154BB0507C**|
|a0.nic.ong.        **172800**    IN    **AAAA**    **2001:500:e:0:0:0:0:1**|a0.nic.ong.        **518400**    IN    **AAAA**    **2001:500:e:0:0:0:0:1**|
|a2.nic.ong.        **172800**    IN    A    199.249.112.1|a0.nic.ong.        **518400**    IN    **A**    **199.19.56.1**|
|a2.nic.ong.        **172800**    IN    AAAA    2001:500:40:0:0:0:0:1|a2.nic.ong.        **518400**    IN    A    199.249.112.1|
|b0.nic.ong.        **172800**    IN    A    199.19.54.1|a2.nic.ong.        **518400**    IN    AAAA    2001:500:40:0:0:0:0:1|
|b0.nic.ong.        **172800**    IN    AAAA    2001:500:c:0:0:0:0:1|b0.nic.ong.        **518400**    IN    A    199.19.54.1|
|b2.nic.ong.        **172800**    IN    A    199.249.120.1|b0.nic.ong.        **518400**    IN    AAAA    2001:500:c:0:0:0:0:1|
|b2.nic.ong.        **172800**    IN    AAAA    2001:500:48:0:0:0:0:1|b2.nic.ong.        **518400**    IN    A    199.249.120.1|
|c0.nic.ong.        **172800**    IN    A    199.19.53.1|b2.nic.ong.        **518400**    IN    AAAA    2001:500:48:0:0:0:0:1|
|c0.nic.ong.        **172800**    IN    AAAA    2001:500:b:0:0:0:0:1|c0.nic.ong.        **518400**    IN    A    199.19.53.1|
|d0.nic.ong.        **172800**    IN    A    199.19.57.1|c0.nic.ong.        **518400**    IN    AAAA    2001:500:b:0:0:0:0:1|
|d0.nic.ong.        **172800**    IN    AAAA    2001:500:f:0:0:0:0:1|d0.nic.ong.        **518400**    IN    A    199.19.57.1|
||d0.nic.ong.        **518400**    IN    AAAA    2001:500:f:0:0:0:0:1|
#
## store
|expected|actual|
|--------|---|
|store.            172800    IN    NS    **e**.nic.store.|store.            172800    IN    NS    **c**.nic.store.|
|store.            172800    IN    NS    **f**.nic.store.|store.            172800    IN    NS    **d**.nic.store.|
|a.nic.store.        **172800**    IN    **A**    **194.169.218.45**|a.nic.store.        **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:45**|
|a.nic.store.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:45**|a.nic.store.        **518400**    IN    **A**    **194.169.218.45**|
|b.nic.store.        **172800**    IN    A    185.24.64.45|b.nic.store.        **518400**    IN    A    185.24.64.45|
|b.nic.store.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:45|b.nic.store.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:45|
|**e**.nic.store.        **172800**    IN    **A**    **212.18.248.45**|**c**.nic.store.        **518400**    IN    **AAAA**    **2a02:e180:3:0:0:0:0:8**|
|**e**.nic.store.        **172800**    IN    **AAAA**    **2a04:2b00:13ee:0:0:0:0:45**|**c**.nic.store.        **518400**    IN    **A**    **185.38.99.8**|
|**f**.nic.store.        **172800**    IN    **A**    **212.18.249.45**|**d**.nic.store.        **518400**    IN    **AAAA**    **2a02:e180:4:0:0:0:0:8**|
|**f**.nic.store.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:45**|**d**.nic.store.        **518400**    IN    **A**    **108.59.161.8**|
#
## onl
|expected|actual|
|--------|---|
|**onl.            86400    IN    DS    15421 7 2 0812A6847A4E529CAB3CD8518BA304E179555CFBD15E8AF7F8641C845F768CF6**||
|a0.nic.onl.        **172800**    IN    A    65.22.136.1|a0.nic.onl.        **518400**    IN    A    65.22.136.1|
|a0.nic.onl.        **172800**    IN    AAAA    2a01:8840:86:0:0:0:0:1|a0.nic.onl.        **518400**    IN    AAAA    2a01:8840:86:0:0:0:0:1|
|a2.nic.onl.        **172800**    IN    **A**    **65.22.139.1**|a2.nic.onl.        **518400**    IN    **AAAA**    **2a01:8840:89:0:0:0:0:1**|
|a2.nic.onl.        **172800**    IN    **AAAA**    **2a01:8840:89:0:0:0:0:1**|a2.nic.onl.        **518400**    IN    **A**    **65.22.139.1**|
|b0.nic.onl.        **172800**    IN    A    65.22.137.1|b0.nic.onl.        **518400**    IN    A    65.22.137.1|
|b0.nic.onl.        **172800**    IN    AAAA    2a01:8840:87:0:0:0:0:1|b0.nic.onl.        **518400**    IN    AAAA    2a01:8840:87:0:0:0:0:1|
|c0.nic.onl.        **172800**    IN    **A**    **65.22.138.1**|c0.nic.onl.        **518400**    IN    **AAAA**    **2a01:8840:88:0:0:0:0:1**|
|c0.nic.onl.        **172800**    IN    **AAAA**    **2a01:8840:88:0:0:0:0:1**|c0.nic.onl.        **518400**    IN    **A**    **65.22.138.1**|
#
## td
|expected|actual|
|--------|---|
||**td.            172800    IN    NS    ns-td.afrinic.net.**|
|**td**.            **172800**    IN    **NS**    **ns-td**.**afrinic**.**net**.|**ns**.**cocca.fr.**        **518400**    IN    **A**    **185**.**17**.**236**.**93**|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.**93**|ns.cocca.fr.        **518400**    IN    A    185.17.236.**123**|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|
|ns-td.afrinic.net.    **172800**    IN    A    196.216.168.31|ns-td.afrinic.net.    **518400**    IN    A    196.216.168.31|
|ns-td.afrinic.net.    **172800**    IN    AAAA    2001:43f8:120:0:0:0:0:31|ns-td.afrinic.net.    **518400**    IN    AAAA    2001:43f8:120:0:0:0:0:31|
|nsa.nic.td.        **172800**    IN    A    154.68.159.246|nsa.nic.td.        **518400**    IN    A    154.68.159.246|
|pch.nic.td.        **172800**    IN    **A**    **204.61.216.129**|pch.nic.td.        **518400**    IN    **AAAA**    **2001:500:14:6129:ad:0:0:1**|
|pch.nic.td.        **172800**    IN    **AAAA**    **2001:500:14:6129:ad:0:0:1**|pch.nic.td.        **518400**    IN    **A**    **204.61.216.129**|
#
## tf
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|e.ext.nic.fr.        **172800**    IN    A    193.176.144.22|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|e.ext.nic.fr.        **172800**    IN    AAAA    2a00:d78:0:102:193:176:144:22|e.ext.nic.fr.        **518400**    IN    A    193.176.144.22|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|e.ext.nic.fr.        **518400**    IN    AAAA    2a00:d78:0:102:193:176:144:22|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## alsace
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## tl
|expected|actual|
|--------|---|
|**tl.            172800    IN    NS    ns.cocca.fr.**||
||**tl.            172800    IN    NS    ns.cocca.fr.**|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|ns.anycast.nic.tl.    **172800**    IN    A    204.61.216.19|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|ns.anycast.nic.tl.    **172800**    IN    AAAA    2001:500:14:6019:ad:0:0:1|ns.anycast.nic.tl.    **518400**    IN    A    204.61.216.19|
||ns.anycast.nic.tl.    **518400**    IN    AAAA    2001:500:14:6019:ad:0:0:1|
#
## xn--mgbt3dhd
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|a.ns.nic.xn--mgbt3dhd.    **172800**    IN    **A**    **72.0.49.9**|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|a.ns.nic.xn--mgbt3dhd.    **172800**    IN    **AAAA**    **2620:171:a01:ad:0:0:0:9**|a.ns.nic.xn--mgbt3dhd.    **518400**    IN    **AAAA**    **2620:171:a01:ad:0:0:0:9**|
|b.ns.nic.xn--mgbt3dhd.    **172800**    IN    A    72.42.113.9|a.ns.nic.xn--mgbt3dhd.    **518400**    IN    **A**    **72.0.49.9**|
|b.ns.nic.xn--mgbt3dhd.    **172800**    IN    AAAA    2620:171:d01:dc:0:0:0:9|b.ns.nic.xn--mgbt3dhd.    **518400**    IN    A    72.42.113.9|
||b.ns.nic.xn--mgbt3dhd.    **518400**    IN    AAAA    2620:171:d01:dc:0:0:0:9|
#
## tr
|expected|actual|
|--------|---|
|tr.            172800    IN    NS    **ns61**.nic.tr.|tr.            172800    IN    NS    **ns91**.nic.tr.|
|ns21.nic.tr.        **172800**    IN    A    213.14.246.2|**tr.            172800    IN    NS    ns92.nic.tr.**|
|ns22.nic.tr.        **172800**    IN    A    213.14.246.6|ns21.nic.tr.        **518400**    IN    A    213.14.246.2|
|ns31.nic.tr.        **172800**    IN    A    31.210.155.2|ns22.nic.tr.        **518400**    IN    A    213.14.246.6|
|ns41.nic.tr.        **172800**    IN    A    185.7.0.2|ns31.nic.tr.        **518400**    IN    A    31.210.155.2|
|**ns41**.nic.tr.        **172800**    IN    AAAA    **2001:a98:10:eeee:0:0:0:41**|ns41.nic.tr.        **518400**    IN    **AAAA    2001:a98:10:eeee:0:0:0:41**|
|ns42.nic.tr.        **172800**    IN    A    185.7.0.3|**ns41.nic.tr.        518400    IN    **A    185.7.0.2|
|**ns42**.nic.tr.        **172800**    IN    AAAA    **2001:a98:10:eeee:0:0:0:42**|**ns42**.nic.tr.        **518400**    IN    AAAA    **2001:a98:10:eeee:0:0:0:42**|
|**ns61**.nic.tr.        **172800**    IN    A    **206**.**51**.**254**.1|ns42.nic.tr.        **518400**    IN    A    185.7.0.3|
|**ns61**.nic.tr.        **172800**    IN    AAAA    **2620:171:804:ad2:0:0:0:1**|**ns91**.nic.tr.        **518400**    IN    AAAA    **2600:2000:3002:0:0:0:0:1**|
||**ns91**.nic.tr.        **518400**    IN    A    **162**.**88**.**54**.1|
||**ns92**.nic.tr.        **518400**    IN    **A    162.88.55.1**|
||**ns92.nic.tr.        518400    IN    **AAAA    **2600:2000:3003:0:0:0:0:1**|
#
## makeup
|expected|actual|
|--------|---|
|makeup.            172800    IN    NS    **a**.**nic**.**makeup**.|makeup.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|makeup.            172800    IN    NS    **b**.**nic**.**makeup**.|makeup.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|makeup.            172800    IN    NS    **c**.**nic**.**makeup**.|makeup.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|makeup.            172800    IN    NS    **d**.**nic**.**makeup**.|makeup.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**makeup.            86400    IN    DS    49310 8 2 335D21FA55D5E1E94AD51A0CD89E8BEF3F034C5F842C2AD0A305ABEDB2603257**||
|**a**.**nic**.**makeup**.        **172800**    IN    A    **194**.**169**.**218**.**116**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**makeup**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:116**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**b.nic.makeup.        172800    IN    **A    **185**.**24**.**64**.**116**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b**.**nic**.**makeup**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:116**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**c**.**nic**.**makeup**.        **172800**    IN    A    **212**.**18**.**248**.**116**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**makeup**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:116**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**d**.**nic**.**makeup**.        **172800**    IN    **A**    **212.18.249.116**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**makeup**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:116**||
#
## kerryproperties
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## tv
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ice
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--9dbq2a
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## bharti
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## yahoo
|expected|actual|
|--------|---|
|yahoo.            172800    IN    NS    **ac1**.**nstld**.**com**.|yahoo.            172800    IN    NS    **ns1**.**dns**.**nic**.**yahoo.**|
|yahoo.            172800    IN    NS    **ac2**.**nstld**.**com**.|yahoo.            172800    IN    NS    **ns2**.**dns**.**nic**.**yahoo.**|
|yahoo.            172800    IN    NS    **ac3**.**nstld**.**com**.|yahoo.            172800    IN    NS    **ns3**.**dns**.**nic**.**yahoo.**|
|yahoo.            172800    IN    NS    **ac4**.**nstld**.**com**.|yahoo.            172800    IN    NS    **ns4**.**dns**.**nic**.**yahoo.**|
|yahoo.            86400    IN    DS    **52260** 8 2 **99DA5ED59CA94FC8C28C5C7A4A817E7FC0C52688B115DCF743FB914BE65BA447**|yahoo.            **172800    IN    NS    ns5.dns.nic.yahoo.**|
|**ac1**.**nstld**.**com**.        **172800**    IN    A    **192**.**42**.**173**.**30**|**yahoo.            172800    IN    NS    ns6.dns.nic.yahoo.**|
|**ac1**.**nstld**.**com**.        **172800**    IN    AAAA    **2001:500:120:0:0:0:0:30**|**yahoo.            **86400    IN    DS    **5785** 8 2 **EF452167E7A3999DC64231CDBD770FCE0B2B977DCF38FF703E7CD2A0044CFDF1**|
|**ac2**.**nstld**.**com**.        **172800**    IN    A    **192**.**42**.**174**.**30**|**yahoo**.**            86400    IN    DS    5785 8 1 978E8A0C7BF8E0171D2E9AA9D610531060399C52**|
|**ac2**.**nstld**.**com**.        **172800**    IN    AAAA    **2001:500:121:0:0:0:0:30**|**ns1**.**dns**.**nic.yahoo.**    **518400**    IN    **AAAA    2610:a1:1071:0:0:0:0:b8**|
|**ac3**.**nstld**.**com**.        **172800**    IN    A    **192**.**42**.**175**.**30**|**ns1.dns.nic.yahoo.    518400    IN    **A    **156**.**154**.**144**.**184**|
|**ac3**.**nstld**.**com**.        **172800**    IN    AAAA    **2001:500:122:0:0:0:0:30**|**ns2**.**dns**.**nic**.**yahoo.**    **518400**    IN    AAAA    **2610:a1:1072:0:0:0:0:b8**|
|**ac4**.**nstld**.**com**.        **172800**    IN    A    **192**.**42**.**176**.**30**|**ns2**.**dns**.**nic**.**yahoo.**    **518400**    IN    A    **156**.**154**.**145**.**184**|
|**ac4**.**nstld**.**com**.        **172800**    IN    AAAA    **2001:500:123:0:0:0:0:30**|**ns3**.**dns**.**nic**.**yahoo.**    **518400**    IN    **A    156.154.159.184**|
||**ns3.dns.nic.yahoo.    518400    IN    **AAAA    **2610:a1:1073:0:0:0:0:b8**|
||**ns4**.**dns**.**nic**.**yahoo.**    **518400**    IN    A    **156**.**154**.**156**.**184**|
||**ns4**.**dns**.**nic**.**yahoo.**    **518400**    IN    AAAA    **2610:a1:1074:0:0:0:0:b8**|
||**ns5**.**dns**.**nic**.**yahoo.**    **518400**    IN    A    **156**.**154**.**157**.**184**|
||**ns5**.**dns**.**nic**.**yahoo.**    **518400**    IN    AAAA    **2610:a1:1075:0:0:0:0:b8**|
||**ns6.dns.nic.yahoo.    518400    IN    A    156.154.158.184**|
||**ns6.dns.nic.yahoo.    518400    IN    AAAA    2610:a1:1076:0:0:0:0:b8**|
#
## scholarships
|expected|actual|
|--------|---|
|**scholarships.        86400    IN    DS    13995 7 2 256E06FC2B128D23408512C44D299E87A383E4460E47F76CBF724BB4B3259B63**||
|a0.nic.scholarships.    **172800**    IN    A    65.22.140.17|a0.nic.scholarships.    **518400**    IN    A    65.22.140.17|
|a0.nic.scholarships.    **172800**    IN    AAAA    2a01:8840:8a:0:0:0:0:17|a0.nic.scholarships.    **518400**    IN    AAAA    2a01:8840:8a:0:0:0:0:17|
|a2.nic.scholarships.    **172800**    IN    A    65.22.143.17|a2.nic.scholarships.    **518400**    IN    **AAAA    2a01:8840:8d:0:0:0:0:17**|
|**a2**.nic.scholarships.    **172800**    IN    AAAA    **2a01:8840:8d:0:0:0:0:17**|**a2.nic.scholarships.    518400    IN    **A    65.22.143.17|
|b0.nic.scholarships.    **172800**    IN    A    65.22.141.17|**b0**.nic.scholarships.    **518400**    IN    AAAA    **2a01:8840:8b:0:0:0:0:17**|
|**b0**.nic.scholarships.    **172800**    IN    AAAA    **2a01:8840:8b:0:0:0:0:17**|b0.nic.scholarships.    **518400**    IN    A    65.22.141.17|
|c0.nic.scholarships.    **172800**    IN    A    65.22.142.17|**c0**.nic.scholarships.    **518400**    IN    AAAA    **2a01:8840:8c:0:0:0:0:17**|
|**c0.nic.scholarships.    172800    IN    AAAA    2a01:8840:8c:0:0:0:0:17**|c0.nic.scholarships.    **518400**    IN    A    65.22.142.17|
#
## tiffany
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## oracle
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## clubmed
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## uz
|expected|actual|
|--------|---|
|ns.uz.            **172800**    IN    A    91.212.89.8|ns.uz.            **518400**    IN    A    91.212.89.8|
|ns2.uz.            **172800**    IN    A    81.95.**225**.**245**|ns2.uz.            **518400**    IN    A    81.95.**224**.**158**|
|ns3.uz.            **172800**    IN    A    195.158.1.22|ns3.uz.            **518400**    IN    A    195.158.1.22|
|ns4.uz.            **172800**    IN    A    185.196.212.7|ns4.uz.            **518400**    IN    A    185.196.212.7|
|ns5.uz.            **172800**    IN    A    217.12.81.129|ns5.uz.            **518400**    IN    A    217.12.81.129|
|ns6.uz.            **172800**    IN    A    83.69.129.33|ns6.uz.            **518400**    IN    A    83.69.129.33|
|ns7.uz.            **172800**    IN    A    104.238.81.247|ns7.uz.            **518400**    IN    A    104.238.81.247|
#
## istanbul
|expected|actual|
|--------|---|
|istanbul.        86400    IN    DS    **61630** **8** 2 **3EBB91801CF0D1A67A84B4F1E265B248A3E3B0459C30D3631955E98A31A430D8**|istanbul.        86400    IN    DS    **30918** **7** **1 71A63CE8688FBE09F16B5B725E38422BD76AA46D**|
|a0.nic.istanbul.    **172800**    IN    A    65.22.144.9|**istanbul.        86400    IN    DS    30918 7 **2 **CF7DCD3ED2B6DD16171AFAE7179C00D43947065AB1820C2EF57DA2A274F03540**|
|a0.nic.istanbul.    **172800**    IN    AAAA    2a01:8840:8e:0:0:0:0:9|a0.nic.istanbul.    **518400**    IN    A    65.22.144.9|
|a2.nic.istanbul.    **172800**    IN    A    65.22.147.9|a0.nic.istanbul.    **518400**    IN    AAAA    2a01:8840:8e:0:0:0:0:9|
|**a2**.nic.istanbul.    **172800**    IN    AAAA    **2a01:8840:91:0:0:0:0:9**|a2.nic.istanbul.    **518400**    IN    **AAAA    2a01:8840:91:0:0:0:0:9**|
|b0.nic.istanbul.    **172800**    IN    A    65.22.145.9|**a2.nic.istanbul.    518400    IN    **A    65.22.147.9|
|**b0**.nic.istanbul.    **172800**    IN    **AAAA**    **2a01:8840:8f:0:0:0:0:9**|**b0**.nic.istanbul.    **518400**    IN    AAAA    **2a01:8840:8f:0:0:0:0:9**|
|**c0**.**nic**.**istanbul**.    **172800    IN    AAAA    2a01:8840:90:0:0:0:0:9**|b0.nic.istanbul.    **518400**    IN    A    65.22.145.9|
|c0.nic.istanbul.    **172800**    IN    **A**    **65.22.146.9**|**c0**.nic.istanbul.    **518400**    IN    **A**    **65**.**22**.**146**.**9**|
||c0.nic.istanbul.    **518400**    IN    **AAAA**    **2a01:8840:90:0:0:0:0:9**|
#
## xn--w4r85el8fhu5dnra
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## ve
|expected|actual|
|--------|---|
|ve.            86400    IN    DS    **2329** **8** 1 **90D2DDD1FB931CBFE9510A110742C3B017932EA5**|ve.            86400    IN    DS    **11958** **7** 1 **947CB68E3EB8A27CF7BC90BD782828CDC6FAFE97**|
||**ve.            86400    IN    DS    11958 7 2 DF4F2FCAF5D7899B6C20518E867A0B13D848E93EBC92194AFA6CD18BA67FC852**|
|ssdns-tld.nic.cl.    **172800**    IN    A    200.7.5.14|**ve.            86400    IN    DS    2329 8 1 90D2DDD1FB931CBFE9510A110742C3B017932EA5**|
|ssdns-tld.nic.cl.    **172800**    IN    AAAA    2001:1398:276:0:200:7:5:14|ssdns-tld.nic.cl.    **518400**    IN    A    200.7.5.14|
|ns3.nic.ve.        **172800**    IN    A    190.9.129.56|ssdns-tld.nic.cl.    **518400**    IN    AAAA    2001:1398:276:0:200:7:5:14|
|ns4.nic.ve.        **172800**    IN    A    190.202.128.43|ns3.nic.ve.        **518400**    IN    A    190.9.129.56|
|ns5.nic.ve.        **172800**    IN    **A**    **45.175.22.88**|ns4.nic.ve.        **518400**    IN    A    190.202.128.43|
|ns5.nic.ve.        **172800**    IN    **AAAA**    **2801:18:8800:3:18ba:beff:fe61:d08b**|ns5.nic.ve.        **518400**    IN    **AAAA**    **2801:18:8800:3:18ba:beff:fe61:d08b**|
|ns6.nic.ve.        **172800**    IN    A    45.175.22.4|ns5.nic.ve.        **518400**    IN    **A**    **45.175.22.88**|
|ns6.nic.ve.        **172800**    IN    AAAA    2801:18:8800:1:0:0:0:4|ns6.nic.ve.        **518400**    IN    A    45.175.22.4|
||ns6.nic.ve.        **518400**    IN    AAAA    2801:18:8800:1:0:0:0:4|
#
## gallup
|expected|actual|
|--------|---|
|gallup.            86400    IN    DS    **34159** **8** **2** **AE9BBA11562A260AAA062E2EB9881443044FDB8998B6A81C25D34D0D6BF49CB5**|gallup.            86400    IN    DS    **23110** **7** **1** **00F395AE705A7870B16482B0426A47BEF6AF6089**|
|**a0.nic.**gallup.        **172800**    IN    **A**    **65.22.168.17**|gallup.            **86400**    IN    **DS**    **23110** **7 2 24D417C21B6927C970EBDC04663366EED8E5E03A6F05453152D70E7633339CC8**|
|a0.nic.gallup.        **172800**    IN    AAAA    2a01:8840:a2:0:0:0:0:17|a0.nic.gallup.        **518400**    IN    AAAA    2a01:8840:a2:0:0:0:0:17|
|**a2**.nic.gallup.        **172800**    IN    A    65.22.**171**.17|**a0**.nic.gallup.        **518400**    IN    A    65.22.**168**.17|
|a2.nic.gallup.        **172800**    IN    AAAA    2a01:8840:a5:0:0:0:0:17|a2.nic.gallup.        **518400**    IN    AAAA    2a01:8840:a5:0:0:0:0:17|
|b0.nic.gallup.        **172800**    IN    A    65.22.169.17|**a2.nic.gallup.        518400    IN    A    65.22.171.17**|
|b0.nic.gallup.        **172800**    IN    AAAA    2a01:8840:a3:0:0:0:0:17|b0.nic.gallup.        **518400**    IN    A    65.22.169.17|
|c0.nic.gallup.        **172800**    IN    **A**    **65.22.170.17**|b0.nic.gallup.        **518400**    IN    AAAA    2a01:8840:a3:0:0:0:0:17|
|c0.nic.gallup.        **172800**    IN    **AAAA**    **2a01:8840:a4:0:0:0:0:17**|c0.nic.gallup.        **518400**    IN    **AAAA**    **2a01:8840:a4:0:0:0:0:17**|
||c0.nic.gallup.        **518400**    IN    **A**    **65.22.170.17**|
#
## sina
|expected|actual|
|--------|---|
|sina.            86400    IN    DS    **39217** **8** 2 **B177DAEF81C0EBD0C85DBA9092550EB8D14333806E1DB4C2C44AC9ECE76432A5**|sina.            86400    IN    DS    **16974** **7** **1 A95E97B13C8C7100566D280F34549762F1E4F429**|
|a0.nic.sina.        **172800**    IN    **A**    **65.22.140.33**|**sina.            86400    IN    DS    16974 7 **2 **67505289EBDE95405EC11BA2821847051C791EE6B5C681728BE44C92B65F14D9**|
|a0.nic.sina.        **172800**    IN    **AAAA**    **2a01:8840:8a:0:0:0:0:33**|a0.nic.sina.        **518400**    IN    **AAAA**    **2a01:8840:8a:0:0:0:0:33**|
|a2.nic.sina.        **172800**    IN    A    65.22.143.33|a0.nic.sina.        **518400**    IN    **A**    **65.22.140.33**|
|a2.nic.sina.        **172800**    IN    AAAA    2a01:8840:8d:0:0:0:0:33|a2.nic.sina.        **518400**    IN    A    65.22.143.33|
|b0.nic.sina.        **172800**    IN    A    65.22.141.33|a2.nic.sina.        **518400**    IN    AAAA    2a01:8840:8d:0:0:0:0:33|
|b0.nic.sina.        **172800**    IN    AAAA    2a01:8840:8b:0:0:0:0:33|b0.nic.sina.        **518400**    IN    A    65.22.141.33|
|c0.nic.sina.        **172800**    IN    A    65.22.142.33|b0.nic.sina.        **518400**    IN    AAAA    2a01:8840:8b:0:0:0:0:33|
|c0.nic.sina.        **172800**    IN    AAAA    2a01:8840:8c:0:0:0:0:33|c0.nic.sina.        **518400**    IN    A    65.22.142.33|
||c0.nic.sina.        **518400**    IN    AAAA    2a01:8840:8c:0:0:0:0:33|
#
## mma
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## edeka
|expected|actual|
|--------|---|
|**edeka.            86400    IN    DS    16659 7 2 79D4AA783D6B41BC667674791135453E47B3274887B21B70E7ACD80FE95F18F7**||
|a0.nic.edeka.        **172800**    IN    A    65.22.16.25|a0.nic.edeka.        **518400**    IN    **AAAA    2a01:8840:12:0:0:0:0:25**|
|**a0**.nic.edeka.        **172800**    IN    AAAA    **2a01:8840:12:0:0:0:0:25**|**a0.nic.edeka.        518400    IN    **A    65.22.16.25|
|a2.nic.edeka.        **172800**    IN    A    65.22.19.25|**a2**.nic.edeka.        **518400**    IN    AAAA    **2a01:8840:15:0:0:0:0:25**|
|**a2.nic.edeka.        172800    IN    AAAA    2a01:8840:15:0:0:0:0:25**|a2.nic.edeka.        **518400**    IN    A    65.22.19.25|
|b0.nic.edeka.        **172800**    IN    A    65.22.17.25|b0.nic.edeka.        **518400**    IN    A    65.22.17.25|
|b0.nic.edeka.        **172800**    IN    AAAA    2a01:8840:13:0:0:0:0:25|b0.nic.edeka.        **518400**    IN    AAAA    2a01:8840:13:0:0:0:0:25|
|c0.nic.edeka.        **172800**    IN    A    65.22.18.25|c0.nic.edeka.        **518400**    IN    A    65.22.18.25|
|c0.nic.edeka.        **172800**    IN    AAAA    2a01:8840:14:0:0:0:0:25|c0.nic.edeka.        **518400**    IN    AAAA    2a01:8840:14:0:0:0:0:25|
#
## swatch
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## verisign
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--fhbei
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## xn--ses554g
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## samsclub
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## kim
|expected|actual|
|--------|---|
|kim.            86400    IN    DS    **12277** **8** 2 **BA18A744991A561AB09A464FF96864573DB04FD61A29E9D37F7551989E7E5535**|kim.            86400    IN    DS    **24474** **7** **1 2DD484EEF79401CBFCA231E6CBF4F1BB165CCE14**|
|a0.nic.kim.        **172800**    IN    A    65.22.28.1|**kim.            86400    IN    DS    24474 7 **2 **2384A0380782DA192D1C1F6DA55A106551EF4C5233CD479536101921D35411E5**|
|a0.nic.kim.        **172800**    IN    AAAA    2a01:8840:1e:0:0:0:0:1|a0.nic.kim.        **518400**    IN    A    65.22.28.1|
|a2.nic.kim.        **172800**    IN    **A**    **65.22.31.1**|a0.nic.kim.        **518400**    IN    AAAA    2a01:8840:1e:0:0:0:0:1|
|a2.nic.kim.        **172800**    IN    **AAAA**    **2a01:8840:21:0:0:0:0:1**|a2.nic.kim.        **518400**    IN    **AAAA**    **2a01:8840:21:0:0:0:0:1**|
|b0.nic.kim.        **172800**    IN    A    65.22.29.1|a2.nic.kim.        **518400**    IN    **A**    **65.22.31.1**|
|b0.nic.kim.        **172800**    IN    AAAA    2a01:8840:1f:0:0:0:0:1|b0.nic.kim.        **518400**    IN    A    65.22.29.1|
|c0.nic.kim.        **172800**    IN    **A**    **65.22.30.1**|b0.nic.kim.        **518400**    IN    AAAA    2a01:8840:1f:0:0:0:0:1|
|c0.nic.kim.        **172800**    IN    **AAAA**    **2a01:8840:20:0:0:0:0:1**|c0.nic.kim.        **518400**    IN    **AAAA**    **2a01:8840:20:0:0:0:0:1**|
||c0.nic.kim.        **518400**    IN    **A**    **65.22.30.1**|
#
## wf
|expected|actual|
|--------|---|
|**wf.            86400    IN    DS    16466 13 2 6A8BDA1B40424D0AE869FC57DE9F003399E792C821D0EFC4FD56ADD4EA5D8534**||
|d.nic.fr.        **172800**    IN    A    194.0.9.1|**wf.            86400    IN    DS    16466 13 2 6A8BDA1B40424D0AE869FC57DE9F003399E792C821D0EFC4FD56ADD4EA5D8534**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|e.ext.nic.fr.        **172800**    IN    A    193.176.144.22|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|e.ext.nic.fr.        **172800**    IN    AAAA    2a00:d78:0:102:193:176:144:22|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|e.ext.nic.fr.        **518400**    IN    A    193.176.144.22|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|e.ext.nic.fr.        **518400**    IN    AAAA    2a00:d78:0:102:193:176:144:22|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
||g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## apple
|expected|actual|
|--------|---|
|apple.            86400    IN    DS    **50166** 7 1 **20DE4DA26E31E393746200E709C6F4E91FE65D4F**|apple.            86400    IN    DS    **64704** 7 1 **B56889E52340692958F9D844FA179E2D0805AF49**|
|apple.            86400    IN    DS    **50166** 7 2 **B8038B6449B548E38FC74CE04D21726C9F052213A55573256C6867AED2E6C091**|apple.            86400    IN    DS    **64704** 7 2 **25F2DC612AA65F739CE8DE6ADF5F6DDBCC53B4FEB66BB18AEF44F3DB2477E328**|
|a0.nic.apple.        **172800**    IN    A    65.22.60.1|a0.nic.apple.        **518400**    IN    A    65.22.60.1|
|a0.nic.apple.        **172800**    IN    AAAA    2a01:8840:3a:0:0:0:0:1|a0.nic.apple.        **518400**    IN    AAAA    2a01:8840:3a:0:0:0:0:1|
|a2.nic.apple.        **172800**    IN    **A**    **65.22.63.1**|a2.nic.apple.        **518400**    IN    **AAAA**    **2a01:8840:3d:0:0:0:0:1**|
|a2.nic.apple.        **172800**    IN    **AAAA**    **2a01:8840:3d:0:0:0:0:1**|a2.nic.apple.        **518400**    IN    **A**    **65.22.63.1**|
|b0.nic.apple.        **172800**    IN    A    65.22.61.1|b0.nic.apple.        **518400**    IN    A    65.22.61.1|
|b0.nic.apple.        **172800**    IN    AAAA    2a01:8840:3b:0:0:0:0:1|b0.nic.apple.        **518400**    IN    AAAA    2a01:8840:3b:0:0:0:0:1|
|c0.nic.apple.        **172800**    IN    **A**    **65.22.62.1**|c0.nic.apple.        **518400**    IN    **AAAA**    **2a01:8840:3c:0:0:0:0:1**|
|c0.nic.apple.        **172800**    IN    **AAAA**    **2a01:8840:3c:0:0:0:0:1**|c0.nic.apple.        **518400**    IN    **A**    **65.22.62.1**|
#
## organic
|expected|actual|
|--------|---|
|organic.        86400    IN    DS    **22474** **8** 2 **5803FBC9F1FC0D4AA172DC24F6B2B099F18DC13E04CEE7F605777D798A3A812F**|organic.        86400    IN    DS    **53418** **7** **1 EE9CB0590F8A62301D2E7D4DB6D5E50405019146**|
|a0.nic.organic.        **172800**    IN    A    65.22.20.40|**organic.        86400    IN    DS    53418 7 **2 **158DA177F06E185437CF0D4C7647206C89C9D6EA73A7F3FE5C5EC004BB0A21C7**|
|a0.nic.organic.        **172800**    IN    AAAA    2a01:8840:16:0:0:0:0:40|a0.nic.organic.        **518400**    IN    A    65.22.20.40|
|a2.nic.organic.        **172800**    IN    A    65.22.23.40|a0.nic.organic.        **518400**    IN    AAAA    2a01:8840:16:0:0:0:0:40|
|**a2**.nic.organic.        **172800**    IN    AAAA    **2a01:8840:19:0:0:0:0:40**|a2.nic.organic.        **518400**    IN    **AAAA    2a01:8840:19:0:0:0:0:40**|
|b0.nic.organic.        **172800**    IN    A    65.22.21.40|**a2.nic.organic.        518400    IN    **A    65.22.23.40|
|**b0.nic.organic.        172800    IN    AAAA    2a01:8840:17:0:0:0:0:40**|**b0**.nic.organic.        **518400**    IN    AAAA    **2a01:8840:17:0:0:0:0:40**|
|c0.nic.organic.        **172800**    IN    A    65.22.22.40|b0.nic.organic.        **518400**    IN    A    65.22.21.40|
|c0.nic.organic.        **172800**    IN    AAAA    2a01:8840:18:0:0:0:0:40|c0.nic.organic.        **518400**    IN    A    65.22.22.40|
||c0.nic.organic.        **518400**    IN    AAAA    2a01:8840:18:0:0:0:0:40|
#
## org
|expected|actual|
|--------|---|
|org.            86400    IN    DS    **26974** **8** 2 **4FEDE294C53F438A158C41D39489CD78A86BEB0D8A0AEAFF14745C0D16E1DE32**|org.            86400    IN    DS    **17883** **7** 2 **D889CAD790F01979E860D6627B58F85AB554E0E491FE06515F35548D1EB4E6EE**|
|a0.org.afilias-nst.info.    **172800**    IN    **A**    **199.19.56.1**|**org.            86400    IN    DS    17883 7 1 38C5CF93B369C7557E0515FAAA57060F1BFB12C1**|
|a0.org.afilias-nst.info.    **172800**    IN    **AAAA**    **2001:500:e:0:0:0:0:1**|a0.org.afilias-nst.info.    **518400**    IN    **AAAA**    **2001:500:e:0:0:0:0:1**|
|a2.org.afilias-nst.info.    **172800**    IN    A    199.249.112.1|a0.org.afilias-nst.info.    **518400**    IN    **A**    **199.19.56.1**|
|a2.org.afilias-nst.info.    **172800**    IN    AAAA    2001:500:40:0:0:0:0:1|a2.org.afilias-nst.info.    **518400**    IN    A    199.249.112.1|
|c0.org.afilias-nst.info.    **172800**    IN    A    199.19.53.1|a2.org.afilias-nst.info.    **518400**    IN    AAAA    2001:500:40:0:0:0:0:1|
|c0.org.afilias-nst.info.    **172800**    IN    AAAA    2001:500:b:0:0:0:0:1|c0.org.afilias-nst.info.    **518400**    IN    A    199.19.53.1|
|b0.org.afilias-nst.org.    **172800**    IN    A    199.19.54.1|c0.org.afilias-nst.info.    **518400**    IN    AAAA    2001:500:b:0:0:0:0:1|
|b0.org.afilias-nst.org.    **172800**    IN    AAAA    2001:500:c:0:0:0:0:1|b0.org.afilias-nst.org.    **518400**    IN    A    199.19.54.1|
|b2.org.afilias-nst.org.    **172800**    IN    A    199.249.120.1|b0.org.afilias-nst.org.    **518400**    IN    AAAA    2001:500:c:0:0:0:0:1|
|b2.org.afilias-nst.org.    **172800**    IN    AAAA    2001:500:48:0:0:0:0:1|b2.org.afilias-nst.org.    **518400**    IN    A    199.249.120.1|
|d0.org.afilias-nst.org.    **172800**    IN    A    199.19.57.1|b2.org.afilias-nst.org.    **518400**    IN    AAAA    2001:500:48:0:0:0:0:1|
|d0.org.afilias-nst.org.    **172800**    IN    AAAA    2001:500:f:0:0:0:0:1|d0.org.afilias-nst.org.    **518400**    IN    A    199.19.57.1|
||d0.org.afilias-nst.org.    **518400**    IN    AAAA    2001:500:f:0:0:0:0:1|
#
## beats
|expected|actual|
|--------|---|
|beats.            86400    IN    DS    **3234** 7 1 **D046927A7B31B59E7AAA612D56E1F8DA77CC9E91**|beats.            86400    IN    DS    **24981** 7 1 **9BA4545436492A1E06699B29BEF8E4BCB18D4017**|
||**beats.            86400    IN    DS    24981 7 2 64E153079D97F281A9B4A8CA8FF12456521EF0C597EEABB3FFE407A811523C13**|
|beats.            86400    IN    DS    **4606** 7 1 **5016CFAFB58908893B6288C1150B6DEBB1C0436F**|beats.            86400    IN    DS    **3234** 7 1 **D046927A7B31B59E7AAA612D56E1F8DA77CC9E91**|
|beats.            **86400**    IN    **DS**    **4606** **7 2 A5F26C1DD2B6F050BF9C1439E0C53295E502769BE20991866084AAEF6BA2ED7D**|**a0.nic.**beats.        **518400**    IN    **AAAA**    **2a01:8840:3a:0:0:0:0:9**|
|a0.nic.beats.        **172800**    IN    A    65.22.60.9|a0.nic.beats.        **518400**    IN    A    65.22.60.9|
|**a0**.nic.beats.        **172800**    IN    AAAA    **2a01:8840:3a:0:0:0:0:9**|**a2**.nic.beats.        **518400**    IN    AAAA    **2a01:8840:3d:0:0:0:0:9**|
|a2.nic.beats.        **172800**    IN    A    65.22.63.9|a2.nic.beats.        **518400**    IN    A    65.22.63.9|
|**a2**.nic.beats.        **172800**    IN    AAAA    **2a01:8840:3d:0:0:0:0:9**|**b0**.nic.beats.        **518400**    IN    AAAA    **2a01:8840:3b:0:0:0:0:9**|
|b0.nic.beats.        **172800**    IN    A    65.22.61.9|b0.nic.beats.        **518400**    IN    A    65.22.61.9|
|**b0**.nic.beats.        **172800**    IN    AAAA    **2a01:8840:3b:0:0:0:0:9**|**c0**.nic.beats.        **518400**    IN    AAAA    **2a01:8840:3c:0:0:0:0:9**|
|c0.nic.beats.        **172800**    IN    A    65.22.62.9|c0.nic.beats.        **518400**    IN    A    65.22.62.9|
|**c0.nic.beats.        172800    IN    AAAA    2a01:8840:3c:0:0:0:0:9**||
#
## forex
|expected|actual|
|--------|---|
|forex.            172800    IN    NS    **a**.**nic**.**forex**.|forex.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|forex.            172800    IN    NS    **b**.**nic**.**forex**.|forex.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|forex.            172800    IN    NS    **c**.**nic**.**forex**.|forex.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|forex.            172800    IN    NS    **d**.**nic**.**forex**.|forex.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**forex**.**            86400    IN    DS    57511 8 2 00B8708F30D23C9FAD8F63F16D88B6A61725C5343AD14425335D3A0416DBF8D0**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**forex.**        **172800**    IN    A    **194**.**169**.**218**.**126**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**a**.**nic**.**forex**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:126**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b.nic.forex.        172800    IN    **A    **185**.**24**.**64**.**126**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**b**.**nic**.**forex**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:126**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**forex**.        **172800**    IN    A    **212**.**18**.**248**.**126**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**c**.**nic**.**forex**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:126**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**forex**.        **172800**    IN    **A**    **212.18.249.126**||
|**d**.**nic**.**forex**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:126**||
#
## fage
|expected|actual|
|--------|---|
|fage.            86400    IN    DS    **17296** **8** 2 **73F0339F6D64BE40A263E66BF730B0EF53A4372978561E0CC8F3CB754DF443FE**|fage.            86400    IN    DS    **2884** **7** **1 622E41AD5CFB87DDFF299334FD73B40570DF2971**|
|a0.nic.fage.        **172800**    IN    A    65.22.156.33|**fage.            86400    IN    DS    2884 7 **2 **FA99578AD0DAD7A8206080917635A27A74C0E583C9DBB108AC64F33B28A90790**|
|a0.nic.fage.        **172800**    IN    AAAA    2a01:8840:9a:0:0:0:0:33|a0.nic.fage.        **518400**    IN    A    65.22.156.33|
|a2.nic.fage.        **172800**    IN    A    65.22.159.33|a0.nic.fage.        **518400**    IN    AAAA    2a01:8840:9a:0:0:0:0:33|
|a2.nic.fage.        **172800**    IN    AAAA    2a01:8840:9d:0:0:0:0:33|a2.nic.fage.        **518400**    IN    A    65.22.159.33|
|b0.nic.fage.        **172800**    IN    A    65.22.157.33|a2.nic.fage.        **518400**    IN    AAAA    2a01:8840:9d:0:0:0:0:33|
|b0.nic.fage.        **172800**    IN    AAAA    2a01:8840:9b:0:0:0:0:33|b0.nic.fage.        **518400**    IN    A    65.22.157.33|
|c0.nic.fage.        **172800**    IN    A    65.22.158.33|b0.nic.fage.        **518400**    IN    AAAA    2a01:8840:9b:0:0:0:0:33|
|c0.nic.fage.        **172800**    IN    AAAA    2a01:8840:9c:0:0:0:0:33|c0.nic.fage.        **518400**    IN    A    65.22.158.33|
||c0.nic.fage.        **518400**    IN    AAAA    2a01:8840:9c:0:0:0:0:33|
#
## bzh
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## jeep
|expected|actual|
|--------|---|
|jeep.            86400    IN    DS    **49999** **8** 2 **F00A0B4B65ADAC570C2DBC81483367392EA9A86FFD17E4B3F042D446ACD1EA4B**|jeep.            86400    IN    DS    **28249** **7** **1 925FD98917369A1BF96CA93F4C861FD274B975D7**|
|a0.nic.jeep.        **172800**    IN    A    65.22.76.41|**jeep.            86400    IN    DS    28249 7 **2 **CC65C119A57F2DA653B1F8B044C331D610C0C2760DB083924912C3AEF71ED771**|
|a0.nic.jeep.        **172800**    IN    AAAA    2a01:8840:4a:0:0:0:0:41|a0.nic.jeep.        **518400**    IN    A    65.22.76.41|
|a2.nic.jeep.        **172800**    IN    A    65.22.79.41|a0.nic.jeep.        **518400**    IN    AAAA    2a01:8840:4a:0:0:0:0:41|
|**a2**.nic.jeep.        **172800**    IN    AAAA    **2a01:8840:4d:0:0:0:0:41**|a2.nic.jeep.        **518400**    IN    **AAAA    2a01:8840:4d:0:0:0:0:41**|
|b0.nic.jeep.        **172800**    IN    A    65.22.77.41|**a2.nic.jeep.        518400    IN    **A    65.22.79.41|
|**b0**.nic.jeep.        **172800**    IN    AAAA    **2a01:8840:4b:0:0:0:0:41**|**b0**.nic.jeep.        **518400**    IN    AAAA    **2a01:8840:4b:0:0:0:0:41**|
|c0.nic.jeep.        **172800**    IN    A    65.22.78.41|b0.nic.jeep.        **518400**    IN    A    65.22.77.41|
|**c0.nic.jeep.        172800    IN    AAAA    2a01:8840:4c:0:0:0:0:41**|**c0**.nic.jeep.        **518400**    IN    AAAA    **2a01:8840:4c:0:0:0:0:41**|
||c0.nic.jeep.        **518400**    IN    A    65.22.78.41|
#
## yt
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|e.ext.nic.fr.        **172800**    IN    A    193.176.144.22|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|e.ext.nic.fr.        **172800**    IN    AAAA    2a00:d78:0:102:193:176:144:22|e.ext.nic.fr.        **518400**    IN    A    193.176.144.22|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|e.ext.nic.fr.        **518400**    IN    AAAA    2a00:d78:0:102:193:176:144:22|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## azure
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## boehringer
|expected|actual|
|--------|---|
|boehringer.        86400    IN    DS    **37117** **8** 2 **98508B91E23EEF16223B93512B6FFD370F83CED809A7A157A98A8B07BE84E0CE**|boehringer.        86400    IN    DS    **7348** **7** **1 AA5C90CDB6C32B24F2167C6E99803E1C57E4E9E3**|
|a0.nic.boehringer.    **172800**    IN    A    65.22.188.17|**boehringer.        86400    IN    DS    7348 7 **2 **5AB79185D38DD02DE1094F45AE43943BFCA4E6CA405ED9C8B78FFB470743BF1A**|
|a0.nic.boehringer.    **172800**    IN    AAAA    2a01:8840:b6:0:0:0:0:17|a0.nic.boehringer.    **518400**    IN    A    65.22.188.17|
|a2.nic.boehringer.    **172800**    IN    A    65.22.191.17|a0.nic.boehringer.    **518400**    IN    AAAA    2a01:8840:b6:0:0:0:0:17|
|a2.nic.boehringer.    **172800**    IN    AAAA    2a01:8840:b9:0:0:0:0:17|a2.nic.boehringer.    **518400**    IN    A    65.22.191.17|
|b0.nic.boehringer.    **172800**    IN    A    65.22.189.17|a2.nic.boehringer.    **518400**    IN    AAAA    2a01:8840:b9:0:0:0:0:17|
|b0.nic.boehringer.    **172800**    IN    AAAA    2a01:8840:b7:0:0:0:0:17|b0.nic.boehringer.    **518400**    IN    A    65.22.189.17|
|c0.nic.boehringer.    **172800**    IN    A    65.22.190.17|b0.nic.boehringer.    **518400**    IN    AAAA    2a01:8840:b7:0:0:0:0:17|
|c0.nic.boehringer.    **172800**    IN    AAAA    2a01:8840:b8:0:0:0:0:17|c0.nic.boehringer.    **518400**    IN    A    65.22.190.17|
||c0.nic.boehringer.    **518400**    IN    AAAA    2a01:8840:b8:0:0:0:0:17|
#
## xn--c1avg
|expected|actual|
|--------|---|
|xn--c1avg.        86400    IN    DS    **16534** **8** 2 **85D1FF435E850DCEF97843FD4CEED2D36CEEC9186DDCBC5FB3BD9AD440D7C398**|xn--c1avg.        86400    IN    DS    **52719** **7** 2 **B8AC6489EE7C49701C11407F87EFEECA08007713ADC44AD22FA8E9799E1DDD7F**|
|a0.nic.xn--c1avg.    **172800**    IN    A    65.22.184.25|**xn--c1avg.        86400    IN    DS    52719 7 1 C77D620EA3E19DA9A433CC46F354848374EFD434**|
|a0.nic.xn--c1avg.    **172800**    IN    AAAA    2a01:8840:b2:0:0:0:0:25|a0.nic.xn--c1avg.    **518400**    IN    A    65.22.184.25|
|a2.nic.xn--c1avg.    **172800**    IN    **A**    **65.22.187.25**|a0.nic.xn--c1avg.    **518400**    IN    AAAA    2a01:8840:b2:0:0:0:0:25|
|a2.nic.xn--c1avg.    **172800**    IN    **AAAA**    **2a01:8840:b5:0:0:0:0:25**|a2.nic.xn--c1avg.    **518400**    IN    **AAAA**    **2a01:8840:b5:0:0:0:0:25**|
|b0.nic.xn--c1avg.    **172800**    IN    A    65.22.185.25|a2.nic.xn--c1avg.    **518400**    IN    **A**    **65.22.187.25**|
|b0.nic.xn--c1avg.    **172800**    IN    AAAA    2a01:8840:b3:0:0:0:0:25|b0.nic.xn--c1avg.    **518400**    IN    A    65.22.185.25|
|c0.nic.xn--c1avg.    **172800**    IN    **A**    **65.22.186.25**|b0.nic.xn--c1avg.    **518400**    IN    AAAA    2a01:8840:b3:0:0:0:0:25|
|c0.nic.xn--c1avg.    **172800**    IN    **AAAA**    **2a01:8840:b4:0:0:0:0:25**|c0.nic.xn--c1avg.    **518400**    IN    **AAAA**    **2a01:8840:b4:0:0:0:0:25**|
||c0.nic.xn--c1avg.    **518400**    IN    **A**    **65.22.186.25**|
#
## ott
|expected|actual|
|--------|---|
|ott.            86400    IN    DS    **39925** **8** 2 **EA35CB20303CA3E610C87E77947BF04693F3E14933C59A60BEFF384BD0CA0654**|ott.            86400    IN    DS    **47394** **7** **1 1DCAABF533A00B9A2CF33426CE8B478ED41BEB96**|
|a0.nic.ott.        **172800**    IN    A    65.22.92.9|**ott.            86400    IN    DS    47394 7 **2 **276D39D5C44B679EEABA00F81B88BE4155EB349A8F590F6A1FB820601DBB4E3D**|
|a0.nic.ott.        **172800**    IN    AAAA    2a01:8840:5a:0:0:0:0:9|a0.nic.ott.        **518400**    IN    A    65.22.92.9|
|a2.nic.ott.        **172800**    IN    A    65.22.95.9|a0.nic.ott.        **518400**    IN    AAAA    2a01:8840:5a:0:0:0:0:9|
|**a2**.nic.ott.        **172800**    IN    AAAA    **2a01:8840:5d:0:0:0:0:9**|a2.nic.ott.        **518400**    IN    **AAAA    2a01:8840:5d:0:0:0:0:9**|
|b0.nic.ott.        **172800**    IN    A    65.22.93.9|**a2.nic.ott.        518400    IN    **A    65.22.95.9|
|**b0.nic.ott.        172800    IN    AAAA    2a01:8840:5b:0:0:0:0:9**|**b0**.nic.ott.        **518400**    IN    AAAA    **2a01:8840:5b:0:0:0:0:9**|
|c0.nic.ott.        **172800**    IN    A    65.22.94.9|b0.nic.ott.        **518400**    IN    A    65.22.93.9|
|c0.nic.ott.        **172800**    IN    AAAA    2a01:8840:5c:0:0:0:0:9|c0.nic.ott.        **518400**    IN    A    65.22.94.9|
||c0.nic.ott.        **518400**    IN    AAAA    2a01:8840:5c:0:0:0:0:9|
#
## fedex
|expected|actual|
|--------|---|
|fedex.            86400    IN    DS    **57511** **8** 2 **13B91145D3199C419B0B4BAFB3938F08388B7B52BF8983C24E068BF63075B68B**|fedex.            86400    IN    DS    **13356** **7** **1 942FDF70E7F4FEB2F8EBB84DE1A55048A5BF4DB7**|
|a0.nic.fedex.        **172800**    IN    A    65.22.228.33|**fedex.            86400    IN    DS    13356 7 **2 **B2A4680B728B4C7CBA02FD29D161C981FDD9DBA002F93C746404965B1065719C**|
|a0.nic.fedex.        **172800**    IN    AAAA    2a01:8840:de:0:0:0:0:33|a0.nic.fedex.        **518400**    IN    A    65.22.228.33|
|a2.nic.fedex.        **172800**    IN    A    65.22.231.33|a0.nic.fedex.        **518400**    IN    AAAA    2a01:8840:de:0:0:0:0:33|
|**a2**.nic.fedex.        **172800**    IN    AAAA    **2a01:8840:e1:0:0:0:0:33**|a2.nic.fedex.        **518400**    IN    **AAAA    2a01:8840:e1:0:0:0:0:33**|
|b0.nic.fedex.        **172800**    IN    A    65.22.229.33|**a2.nic.fedex.        518400    IN    **A    65.22.231.33|
|**b0.nic.fedex.        172800    IN    AAAA    2a01:8840:df:0:0:0:0:33**|**b0**.nic.fedex.        **518400**    IN    AAAA    **2a01:8840:df:0:0:0:0:33**|
|c0.nic.fedex.        **172800**    IN    A    65.22.230.33|b0.nic.fedex.        **518400**    IN    A    65.22.229.33|
|c0.nic.fedex.        **172800**    IN    AAAA    2a01:8840:e0:0:0:0:0:33|c0.nic.fedex.        **518400**    IN    A    65.22.230.33|
||c0.nic.fedex.        **518400**    IN    AAAA    2a01:8840:e0:0:0:0:0:33|
#
## nationwide
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## zw
|expected|actual|
|--------|---|
|**zw.            172800    IN    NS    ns1.telone.co.zw.**||
|zw.            172800    IN    NS    **ns2**.telone.co.zw.|zw.            172800    IN    NS    **ns1**.telone.co.zw.|
||**zw.            172800    IN    NS    ns2.telone.co.zw.**|
|**zw**.**            172800    IN    NS    ns1zim**.**telone**.**co.zw.**|**ns1**.**liquidtelecom**.**net**.    **518400**    IN    **A**    **5**.**11**.**11**.**1**|
|**zw.**            **172800    **IN    **NS**    **ns2zim**.**telone**.**co**.**zw.**|ns1.liquidtelecom.net.    **518400**    IN    **AAAA**    **2c0f:fe40:0:0:5:11:11:1**|
|ns1.liquidtelecom.net.    **172800**    IN    **A**    **5.11.11.1**|**ns2**.liquidtelecom.net.    **518400**    IN    AAAA    **2c0f:fe40:0:0:5:11:11:10**|
|**ns1**.liquidtelecom.net.    **172800**    IN    AAAA    **2c0f:fe40:0:0:5:11:11:1**|ns2.liquidtelecom.net.    **518400**    IN    A    5.11.11.10|
|ns2.liquidtelecom.net.    **172800**    IN    A    5.11.11.10|**zw-ns**.**anycast**.**pch.**net.    **518400**    IN    AAAA    **2001:500:14:6128:ad:0:0:1**|
|**ns2**.**liquidtelecom**.net.    **172800**    IN    AAAA    **2c0f:fe40:0:0:5:11:11:10**|zw-ns.anycast.pch.net.    **518400**    IN    A    204.61.216.128|
|zw-ns.anycast.pch.net.    **172800**    IN    A    204.61.216.128|ns1.telone.co.zw.    **518400**    IN    A    194.133.122.47|
|**zw-ns.anycast.pch.net.    172800    IN    AAAA    2001:500:14:6128:ad:0:0:1**|ns1.telone.co.zw.    **518400**    IN    AAAA    2c0f:f758:0:13:0:0:0:47|
|ns1.telone.co.zw.    **172800**    IN    A    194.133.122.47|**ns2**.telone.co.zw.    **518400**    IN    AAAA    **2c0f:f758:0:13:0:0:0:42**|
|ns1.telone.co.zw.    **172800**    IN    AAAA    2c0f:f758:0:13:0:0:0:47|ns2.telone.co.zw.    **518400**    IN    A    194.133.122.42|
|**ns1zim**.telone.co.zw.    **172800**    IN    **A    41.220.30.81**||
|**ns1zim.telone.co.zw.    172800    IN    **AAAA    **2c0f:f758:0:a:0:0:0:81**||
|ns2.telone.co.zw.    **172800**    IN    A    194.133.122.42||
|**ns2.telone.co.zw.    172800    IN    AAAA    2c0f:f758:0:13:0:0:0:42**||
|**ns2zim.telone.co.zw.    172800    IN    A    41.220.30.82**||
|**ns2zim.telone.co.zw.    172800    IN    AAAA    2c0f:f758:0:a:0:0:0:82**||
#
## lgbt
|expected|actual|
|--------|---|
|lgbt.            86400    IN    DS    **16912** **8** 2 **58FC6791DAA780F1B589FB72CE7F1E43F39DCD185DF0E57AE60178E81FA174B6**|lgbt.            86400    IN    DS    **58564** **7** **1 CEC20DEC329596BF1ABA47BA1CA47EBAA1AB543B**|
|a0.nic.lgbt.        **172800**    IN    AAAA    2a01:8840:22:0:0:0:0:1|**lgbt.            86400    IN    DS    58564 7 **2 **40C36C222C2CDA089502F1F320C49DADE0237F269A2B8F4EF5906A3DF1707CA8**|
|a0.nic.lgbt.        **172800**    IN    A    65.22.32.1|a0.nic.lgbt.        **518400**    IN    AAAA    2a01:8840:22:0:0:0:0:1|
|a2.nic.lgbt.        **172800**    IN    A    65.22.35.1|a0.nic.lgbt.        **518400**    IN    A    65.22.32.1|
|a2.nic.lgbt.        **172800**    IN    AAAA    2a01:8840:25:0:0:0:0:1|a2.nic.lgbt.        **518400**    IN    A    65.22.35.1|
|b0.nic.lgbt.        **172800**    IN    A    65.22.33.1|a2.nic.lgbt.        **518400**    IN    AAAA    2a01:8840:25:0:0:0:0:1|
|b0.nic.lgbt.        **172800**    IN    AAAA    2a01:8840:23:0:0:0:0:1|b0.nic.lgbt.        **518400**    IN    A    65.22.33.1|
|c0.nic.lgbt.        **172800**    IN    **A**    **65.22.34.1**|b0.nic.lgbt.        **518400**    IN    AAAA    2a01:8840:23:0:0:0:0:1|
|c0.nic.lgbt.        **172800**    IN    **AAAA**    **2a01:8840:24:0:0:0:0:1**|c0.nic.lgbt.        **518400**    IN    **AAAA**    **2a01:8840:24:0:0:0:0:1**|
||c0.nic.lgbt.        **518400**    IN    **A**    **65.22.34.1**|
#
## gea
|expected|actual|
|--------|---|
|gea.            172800    IN    NS    **a**.**dns.**nic.gea.|gea.            172800    IN    NS    **a0**.nic.gea.|
|gea.            172800    IN    NS    **m**.**dns.**nic.gea.|gea.            172800    IN    NS    **a2**.nic.gea.|
|gea.            172800    IN    NS    **n**.**dns.**nic.gea.|gea.            172800    IN    NS    **b0**.nic.gea.|
|gea.            **86400**    IN    **DS**    **1696** **7 2 961BCDC4141B8D37EBCE830773FADB2994F929B32041A588AE6892104C4020CB**|gea.            **172800**    IN    **NS**    **c0.nic.gea.**|
|gea.            86400    IN    DS    **35421** 7 1 **4635902769A94709C761B62BDFD2ADD2361D4502**|gea.            86400    IN    DS    **10125** 7 1 **B3F7174F912EE39BBEA6617155F123972A70499F**|
|gea.            86400    IN    DS    **35421** 7 2 **38F69F2D629AF44001B3DD9813119C6E1B49F1FECBDC638B3BF73F2B2491BA80**|gea.            86400    IN    DS    **10125** 7 2 **7EF0D08AB7BBE4E44745BA5ED584F63E6FD5A41870C8AC4074008423B829BA9A**|
|**a**.**dns.**nic.gea.        **172800**    IN    A    **194**.**0**.**25**.**33**|**a0**.nic.gea.        **518400**    IN    A    **65**.**22**.**232**.**1**|
|**a**.**dns.**nic.gea.        **172800**    IN    AAAA    **2001:678:20:0:0:0:0:33**|**a0**.nic.gea.        **518400**    IN    AAAA    **2a01:8840:e2:0:0:0:0:1**|
|**m**.**dns**.nic.gea.        **172800**    IN    A    **194**.**0**.**26**.**13**|**a2**.**nic**.**gea.        518400    IN    AAAA    2a01:8840:e5:0:0:0:0:1**|
|**m**.**dns**.nic.gea.        **172800**    IN    AAAA    **2001:67c:10e0:0:0:0:0:13**|**a2.**nic.gea.        **518400**    IN    A    **65**.**22**.**235**.**1**|
|**n**.**dns.**nic.gea.        **172800**    IN    A    **194**.**0**.**24**.**13**|**b0**.**nic**.**gea.        518400    IN    A    65.22.233.1**|
|**n**.**dns.**nic.gea.        **172800**    IN    AAAA    **2001:678:24:0:0:0:0:13**|**b0.**nic.gea.        **518400**    IN    AAAA    **2a01:8840:e3:0:0:0:0:1**|
||**c0**.nic.gea.        **518400**    IN    A    **65**.**22**.**234**.**1**|
||**c0**.nic.gea.        **518400**    IN    AAAA    **2a01:8840:e4:0:0:0:0:1**|
#
## pictet
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## promo
|expected|actual|
|--------|---|
|promo.            86400    IN    DS    **61459** **8** 2 **583DCFFEACF0CF25F52E5F4D356DB7E3D3E4145992EDC4E8B1FEA3B5AD1868CA**|promo.            86400    IN    DS    **5128** **7** **1 E1D76869DEF1939A76CFFD67466261F93441F2B1**|
|a0.nic.promo.        **172800**    IN    **A**    **65.22.244.9**|**promo.            86400    IN    DS    5128 7 **2 **13E88F46A7E0BF4B9AD1DA027A83DA53D745C845430A55DE3025F7C9B4BDAA08**|
|a0.nic.promo.        **172800**    IN    **AAAA**    **2a01:8840:ee:0:0:0:0:9**|a0.nic.promo.        **518400**    IN    **AAAA**    **2a01:8840:ee:0:0:0:0:9**|
|a2.nic.promo.        **172800**    IN    A    65.22.247.9|a0.nic.promo.        **518400**    IN    **A**    **65.22.244.9**|
|a2.nic.promo.        **172800**    IN    AAAA    2a01:8840:f1:0:0:0:0:9|a2.nic.promo.        **518400**    IN    A    65.22.247.9|
|b0.nic.promo.        **172800**    IN    A    65.22.245.9|a2.nic.promo.        **518400**    IN    AAAA    2a01:8840:f1:0:0:0:0:9|
|b0.nic.promo.        **172800**    IN    AAAA    2a01:8840:ef:0:0:0:0:9|b0.nic.promo.        **518400**    IN    A    65.22.245.9|
|c0.nic.promo.        **172800**    IN    **A**    **65.22.246.9**|b0.nic.promo.        **518400**    IN    AAAA    2a01:8840:ef:0:0:0:0:9|
|c0.nic.promo.        **172800**    IN    **AAAA**    **2a01:8840:f0:0:0:0:0:9**|c0.nic.promo.        **518400**    IN    **AAAA**    **2a01:8840:f0:0:0:0:0:9**|
||c0.nic.promo.        **518400**    IN    **A**    **65.22.246.9**|
#
## archi
|expected|actual|
|--------|---|
||**archi.            86400    IN    DS    11134 8 1 5B998950C57C68A0BAB93200A187FCDCD079BEE1**|
|a0.nic.archi.        **172800**    IN    **A**    **65.22.84.1**|a0.nic.archi.        **518400**    IN    **AAAA**    **2a01:8840:52:0:0:0:0:1**|
|a0.nic.archi.        **172800**    IN    **AAAA**    **2a01:8840:52:0:0:0:0:1**|a0.nic.archi.        **518400**    IN    **A**    **65.22.84.1**|
|a2.nic.archi.        **172800**    IN    A    65.22.87.1|a2.nic.archi.        **518400**    IN    A    65.22.87.1|
|a2.nic.archi.        **172800**    IN    AAAA    2a01:8840:55:0:0:0:0:1|a2.nic.archi.        **518400**    IN    AAAA    2a01:8840:55:0:0:0:0:1|
|b0.nic.archi.        **172800**    IN    A    65.22.85.1|b0.nic.archi.        **518400**    IN    A    65.22.85.1|
|b0.nic.archi.        **172800**    IN    AAAA    2a01:8840:53:0:0:0:0:1|b0.nic.archi.        **518400**    IN    AAAA    2a01:8840:53:0:0:0:0:1|
|c0.nic.archi.        **172800**    IN    A    65.22.86.1|c0.nic.archi.        **518400**    IN    A    65.22.86.1|
|c0.nic.archi.        **172800**    IN    AAAA    2a01:8840:54:0:0:0:0:1|c0.nic.archi.        **518400**    IN    AAAA    2a01:8840:54:0:0:0:0:1|
#
## ovh
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## site
|expected|actual|
|--------|---|
|site.            172800    IN    NS    **e**.nic.site.|site.            172800    IN    NS    **c**.nic.site.|
|site.            172800    IN    NS    **f**.nic.site.|site.            172800    IN    NS    **d**.nic.site.|
|a.nic.site.        **172800**    IN    A    194.169.218.61|a.nic.site.        **518400**    IN    A    194.169.218.61|
|a.nic.site.        **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:61|a.nic.site.        **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:61|
|b.nic.site.        **172800**    IN    A    185.24.64.61|b.nic.site.        **518400**    IN    **AAAA    2a04:2b00:13cc:0:0:0:1:61**|
|**b**.nic.site.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:61**|**b.nic.site.        518400    IN    **A    185.24.64.61|
|**e**.nic.site.        **172800**    IN    A    **212**.**18**.**248**.**61**|**c**.nic.site.        **518400**    IN    AAAA    **2a02:e180:3:0:0:0:0:5**|
|**e**.nic.site.        **172800**    IN    **AAAA    2a04:2b00:13ee:0:0:0:0:61**|**c**.nic.site.        **518400**    IN    A    **185**.**38**.**99**.**5**|
|**f.nic.site.        172800    IN    **A    **212**.**18**.**249**.**61**|**d**.nic.site.        **518400**    IN    A    **108**.**59**.**161**.**5**|
|**f**.nic.site.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:61**|**d**.nic.site.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:5**|
#
## msd
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## data
|expected|actual|
|--------|---|
|data.            86400    IN    DS    **31144** **8** **2** **C9BB359F8D99FB1AE7CF5A5972BD18448EE89775E7B6FB0BD19D3BEC970A4E8B**|data.            86400    IN    DS    **60934** **7** **1** **7ECC07118E9BAFB58BACD6528084522DE4D912C3**|
|**a0.nic.**data.        **172800**    IN    **A**    **65.22.96.25**|data.            **86400**    IN    **DS**    **60934** **7 2 95E7AF062BCB85C926F0F69268DC74A161209E67EEC273A6EED55E04F0624A97**|
|a0.nic.data.        **172800**    IN    AAAA    2a01:8840:5e:0:0:0:0:25|a0.nic.data.        **518400**    IN    AAAA    2a01:8840:5e:0:0:0:0:25|
|**a2**.nic.data.        **172800**    IN    A    65.22.**99**.25|**a0**.nic.data.        **518400**    IN    A    65.22.**96**.25|
|a2.nic.data.        **172800**    IN    AAAA    2a01:8840:61:0:0:0:0:25|a2.nic.data.        **518400**    IN    AAAA    2a01:8840:61:0:0:0:0:25|
|**b0**.nic.data.        **172800**    IN    A    65.22.**97**.25|**a2**.nic.data.        **518400**    IN    A    65.22.**99**.25|
|b0.nic.data.        **172800**    IN    AAAA    2a01:8840:5f:0:0:0:0:25|b0.nic.data.        **518400**    IN    AAAA    2a01:8840:5f:0:0:0:0:25|
|**c0**.nic.data.        **172800**    IN    A    65.22.**98**.25|**b0**.nic.data.        **518400**    IN    A    65.22.**97**.25|
|c0.nic.data.        **172800**    IN    AAAA    2a01:8840:60:0:0:0:0:25|c0.nic.data.        **518400**    IN    AAAA    2a01:8840:60:0:0:0:0:25|
||**c0.nic.data.        518400    IN    A    65.22.98.25**|
#
## lamborghini
|expected|actual|
|--------|---|
|**lamborghini.        86400    IN    DS    3475 7 2 2172B3A462504D0AD87D02A202F4DBCDA0A928C9063BF1371348A6B38AA41397**||
|a0.nic.lamborghini.    **172800**    IN    A    65.22.208.33|a0.nic.lamborghini.    **518400**    IN    **AAAA    2a01:8840:ca:0:0:0:0:33**|
|**a0**.nic.lamborghini.    **172800**    IN    AAAA    **2a01:8840:ca:0:0:0:0:33**|**a0.nic.lamborghini.    518400    IN    **A    65.22.208.33|
|a2.nic.lamborghini.    **172800**    IN    A    65.22.211.33|**a2**.nic.lamborghini.    **518400**    IN    AAAA    **2a01:8840:cd:0:0:0:0:33**|
|**a2**.nic.lamborghini.    **172800**    IN    AAAA    **2a01:8840:cd:0:0:0:0:33**|a2.nic.lamborghini.    **518400**    IN    A    65.22.211.33|
|b0.nic.lamborghini.    **172800**    IN    A    65.22.209.33|**b0**.nic.lamborghini.    **518400**    IN    AAAA    **2a01:8840:cb:0:0:0:0:33**|
|**b0**.nic.lamborghini.    **172800**    IN    AAAA    **2a01:8840:cb:0:0:0:0:33**|b0.nic.lamborghini.    **518400**    IN    A    65.22.209.33|
|c0.nic.lamborghini.    **172800**    IN    A    65.22.210.33|**c0**.nic.lamborghini.    **518400**    IN    AAAA    **2a01:8840:cc:0:0:0:0:33**|
|**c0.nic.lamborghini.    172800    IN    AAAA    2a01:8840:cc:0:0:0:0:33**|c0.nic.lamborghini.    **518400**    IN    A    65.22.210.33|
#
## space
|expected|actual|
|--------|---|
|space.            172800    IN    NS    **e**.nic.space.|space.            172800    IN    NS    **c**.nic.space.|
|space.            172800    IN    NS    **f**.nic.space.|space.            172800    IN    NS    **d**.nic.space.|
|a.nic.space.        **172800**    IN    A    194.169.218.51|a.nic.space.        **518400**    IN    A    194.169.218.51|
|a.nic.space.        **172800**    IN    AAAA    2001:67c:13cc:0:0:0:1:51|a.nic.space.        **518400**    IN    AAAA    2001:67c:13cc:0:0:0:1:51|
|b.nic.space.        **172800**    IN    A    185.24.64.51|b.nic.space.        **518400**    IN    A    185.24.64.51|
|b.nic.space.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:51|b.nic.space.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:51|
|**e**.nic.space.        **172800**    IN    **A**    **212.18.248.51**|**c**.nic.space.        **518400**    IN    **AAAA**    **2a02:e180:3:0:0:0:0:4**|
|**e**.nic.space.        **172800**    IN    **AAAA**    **2a04:2b00:13ee:0:0:0:0:51**|**c**.nic.space.        **518400**    IN    **A**    **185.38.99.4**|
|**f**.nic.space.        **172800**    IN    A    **212**.**18**.**249**.**51**|**d**.nic.space.        **518400**    IN    A    **108**.**59**.**161**.**4**|
|**f**.nic.space.        **172800**    IN    AAAA    **2a04:2b00:13ff:0:0:0:0:51**|**d**.nic.space.        **518400**    IN    AAAA    **2a02:e180:4:0:0:0:0:4**|
#
## eco
|expected|actual|
|--------|---|
|eco.            86400    IN    DS    **6925** **8** 2 **1AC66EE24A758B8DF7AC8473D8AE26ACEFEB1E8B51486F846875EF6020A0FD15**|eco.            86400    IN    DS    **58611** **7** **1 68F1D907FD681333F86712F1FE03E8AE17EA2EAF**|
|a0.nic.eco.        **172800**    IN    A    65.22.216.17|**eco.            86400    IN    DS    58611 7 **2 **68C4AD6711006396B87D983573ECFDE8A92BF547DF72ECA7FA43ADE76F729CE9**|
|a0.nic.eco.        **172800**    IN    AAAA    2a01:8840:d2:0:0:0:0:17|a0.nic.eco.        **518400**    IN    A    65.22.216.17|
|a2.nic.eco.        **172800**    IN    **A**    **65.22.219.17**|a0.nic.eco.        **518400**    IN    AAAA    2a01:8840:d2:0:0:0:0:17|
|a2.nic.eco.        **172800**    IN    **AAAA**    **2a01:8840:d5:0:0:0:0:17**|a2.nic.eco.        **518400**    IN    **AAAA**    **2a01:8840:d5:0:0:0:0:17**|
|b0.nic.eco.        **172800**    IN    A    65.22.217.17|a2.nic.eco.        **518400**    IN    **A**    **65.22.219.17**|
|b0.nic.eco.        **172800**    IN    AAAA    2a01:8840:d3:0:0:0:0:17|b0.nic.eco.        **518400**    IN    A    65.22.217.17|
|c0.nic.eco.        **172800**    IN    A    65.22.218.17|b0.nic.eco.        **518400**    IN    AAAA    2a01:8840:d3:0:0:0:0:17|
|c0.nic.eco.        **172800**    IN    AAAA    2a01:8840:d4:0:0:0:0:17|c0.nic.eco.        **518400**    IN    A    65.22.218.17|
||c0.nic.eco.        **518400**    IN    AAAA    2a01:8840:d4:0:0:0:0:17|
#
## xn--p1acf
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|ns1.nic.xn--p1acf.    **172800**    IN    A    72.42.113.2|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|ns1.nic.xn--p1acf.    **172800**    IN    AAAA    2620:171:d01:dc:0:0:0:2|ns1.nic.xn--p1acf.    **518400**    IN    A    72.42.113.2|
|ns2.nic.xn--p1acf.    **172800**    IN    **A**    **72.0.49.2**|ns1.nic.xn--p1acf.    **518400**    IN    AAAA    2620:171:d01:dc:0:0:0:2|
|ns2.nic.xn--p1acf.    **172800**    IN    **AAAA**    **2620:171:a01:ad:0:0:0:2**|ns2.nic.xn--p1acf.    **518400**    IN    **AAAA**    **2620:171:a01:ad:0:0:0:2**|
||ns2.nic.xn--p1acf.    **518400**    IN    **A**    **72.0.49.2**|
#
## xin
|expected|actual|
|--------|---|
|**xin.            86400    IN    DS    31863 7 2 AE18BAE0E30E2BB51E5514F1B42A761C40DF079BEA0EB95FB584EE38ECD224B8**||
|a0.nic.xin.        **172800**    IN    **A**    **65.22.128.17**|a0.nic.xin.        **518400**    IN    **AAAA**    **2a01:8840:7e:0:0:0:0:17**|
|a0.nic.xin.        **172800**    IN    **AAAA**    **2a01:8840:7e:0:0:0:0:17**|a0.nic.xin.        **518400**    IN    **A**    **65.22.128.17**|
|a2.nic.xin.        **172800**    IN    A    65.22.131.17|a2.nic.xin.        **518400**    IN    A    65.22.131.17|
|a2.nic.xin.        **172800**    IN    AAAA    2a01:8840:81:0:0:0:0:17|a2.nic.xin.        **518400**    IN    AAAA    2a01:8840:81:0:0:0:0:17|
|b0.nic.xin.        **172800**    IN    A    65.22.129.17|b0.nic.xin.        **518400**    IN    A    65.22.129.17|
|b0.nic.xin.        **172800**    IN    AAAA    2a01:8840:7f:0:0:0:0:17|b0.nic.xin.        **518400**    IN    AAAA    2a01:8840:7f:0:0:0:0:17|
|c0.nic.xin.        **172800**    IN    A    65.22.130.17|c0.nic.xin.        **518400**    IN    A    65.22.130.17|
|c0.nic.xin.        **172800**    IN    AAAA    2a01:8840:80:0:0:0:0:17|c0.nic.xin.        **518400**    IN    AAAA    2a01:8840:80:0:0:0:0:17|
#
## viking
|expected|actual|
|--------|---|
|**viking.            86400    IN    DS    50971 8 2 1809DBA33D16E851270758C3EF774D65984AF94F7C3DE9B3470167CE19C22DEF**||
|**a0**.**nic.**viking.        **172800**    IN    **A**    **65**.**22**.**192**.**17**|**viking**.**            86400    IN    DS    37348 7 1 4176BBD41C159D1502F2FCFC3D07D67019244775**|
|a0.nic.viking.        **172800**    IN    **AAAA**    **2a01:8840:ba:0:0:0:0:17**|viking.            **86400**    IN    **DS**    **37348 7 2 614055F663B3260C4E105B6618244DFF7D3523DBBF71F0C37760A31EC87C70C6**|
|a2.nic.viking.        **172800**    IN    A    65.22.195.17|**a0**.**nic**.**viking**.        **518400    IN    AAAA    2a01:8840:ba:0:0:0:0:17**|
|a2.nic.viking.        **172800**    IN    AAAA    2a01:8840:bd:0:0:0:0:17|a0.nic.viking.        **518400**    IN    **A**    **65.22.192.17**|
|b0.nic.viking.        **172800**    IN    **A**    **65.22.193.17**|a2.nic.viking.        **518400**    IN    A    65.22.195.17|
|b0.nic.viking.        **172800**    IN    **AAAA**    **2a01:8840:bb:0:0:0:0:17**|a2.nic.viking.        **518400**    IN    AAAA    2a01:8840:bd:0:0:0:0:17|
|c0.nic.viking.        **172800**    IN    A    65.22.194.17|b0.nic.viking.        **518400**    IN    **AAAA**    **2a01:8840:bb:0:0:0:0:17**|
|c0.nic.viking.        **172800**    IN    AAAA    2a01:8840:bc:0:0:0:0:17|b0.nic.viking.        **518400**    IN    **A**    **65.22.193.17**|
||c0.nic.viking.        **518400**    IN    A    65.22.194.17|
||c0.nic.viking.        **518400**    IN    AAAA    2a01:8840:bc:0:0:0:0:17|
#
## lotto
|expected|actual|
|--------|---|
|lotto.            86400    IN    DS    **45466** **8** 2 **6FFE76934A3634A61F99FAD76FA0506A7682C5541452CF7B289F348FEDD124BF**|lotto.            86400    IN    DS    **7423** **7** **1 710366ED9BC579189753497510F1AD9E5B8F11CC**|
|a0.nic.lotto.        **172800**    IN    **A**    **65.22.28.25**|**lotto.            86400    IN    DS    7423 7 **2 **6AB77222150520EE2C05B26EE79292E996D62A78F0F41FFE4B0FB6F8FC6A6C72**|
|a0.nic.lotto.        **172800**    IN    **AAAA**    **2a01:8840:1e:0:0:0:0:25**|a0.nic.lotto.        **518400**    IN    **AAAA**    **2a01:8840:1e:0:0:0:0:25**|
|a2.nic.lotto.        **172800**    IN    A    65.22.31.25|a0.nic.lotto.        **518400**    IN    **A**    **65.22.28.25**|
|a2.nic.lotto.        **172800**    IN    AAAA    2a01:8840:21:0:0:0:0:25|a2.nic.lotto.        **518400**    IN    A    65.22.31.25|
|b0.nic.lotto.        **172800**    IN    A    65.22.29.25|a2.nic.lotto.        **518400**    IN    AAAA    2a01:8840:21:0:0:0:0:25|
|b0.nic.lotto.        **172800**    IN    AAAA    2a01:8840:1f:0:0:0:0:25|b0.nic.lotto.        **518400**    IN    A    65.22.29.25|
|c0.nic.lotto.        **172800**    IN    A    65.22.30.25|b0.nic.lotto.        **518400**    IN    AAAA    2a01:8840:1f:0:0:0:0:25|
|c0.nic.lotto.        **172800**    IN    AAAA    2a01:8840:20:0:0:0:0:25|c0.nic.lotto.        **518400**    IN    A    65.22.30.25|
||c0.nic.lotto.        **518400**    IN    AAAA    2a01:8840:20:0:0:0:0:25|
#
## mtr
|expected|actual|
|--------|---|
|ns1.nic.mtr.        **172800**    IN    A    203.119.2.164|ns1.nic.mtr.        **518400**    IN    A    203.119.2.164|
|ns1.nic.mtr.        **172800**    IN    AAAA    2001:dca:4000:0:0:0:cb77:2a4|ns1.nic.mtr.        **518400**    IN    AAAA    2001:dca:4000:0:0:0:cb77:2a4|
|ns2.nic.mtr.        **172800**    IN    A    203.119.87.164|ns2.nic.mtr.        **518400**    IN    A    203.119.87.164|
|ns2.nic.mtr.        **172800**    IN    AAAA    2001:dca:2000:0:0:0:cb77:57a4|ns2.nic.mtr.        **518400**    IN    AAAA    2001:dca:2000:0:0:0:cb77:57a4|
|ns3.nic.mtr.        **172800**    IN    A    169.54.247.173|ns3.nic.mtr.        **518400**    IN    A    169.54.247.173|
|ns3.nic.mtr.        **172800**    IN    AAAA    2607:f0d0:1b02:b9:0:0:0:4|ns3.nic.mtr.        **518400**    IN    AAAA    2607:f0d0:1b02:b9:0:0:0:4|
|ns4.nic.mtr.        **172800**    IN    A    **135**.**90**.**90**.**24**|ns4.nic.mtr.        **518400**    IN    A    **168**.**1**.**115**.**234**|
|ns4.nic.mtr.        **172800**    IN    AAAA    **2401:c900:2101:2a:0:0:0:b**|ns4.nic.mtr.        **518400**    IN    AAAA    **2401:c900:1301:10e:0:0:0:2**|
#
## brussels
|expected|actual|
|--------|---|
|**brussels.        86400    IN    DS    28780 8 2 EA50CAB83940B6AA791BD1A0C47ABD6C8549D43CF2776A48FAC633260F3BEE93**||
|**c**.**ns**.**dns.be.**        **172800**    IN    **A**    **194**.**0.43.**1|**brussels**.**        86400    IN    DS    62419 8 1 C194D0F3AA4F21173994BA410927BBDCFC68D300**|
|c.ns.dns.be.        **172800**    IN    AAAA    2001:678:68:0:0:0:0:1|**brussels**.        **86400**    IN    **DS**    **28780 8 2 EA50CAB83940B6AA791BD1A0C47ABD6C8549D43CF2776A48FAC633260F3BEE93**|
|**d**.ns.dns.be.        **172800**    IN    A    194.0.**44**.1|**brussels**.**        86400    IN    DS    28780 8 **1 **76658C5172912A8D8E4D6FB5948DD1C45833BA08**|
|d.ns.dns.be.        **172800**    IN    AAAA    2001:678:6c:0:0:0:0:1|c.ns.dns.be.        **518400**    IN    AAAA    2001:678:68:0:0:0:0:1|
|y.ns.dns.be.        **172800**    IN    A    120.29.253.8|**c**.ns.dns.be.        **518400**    IN    A    194.0.**43**.1|
|y.ns.dns.be.        **172800**    IN    AAAA    2001:dcd:7:0:0:0:0:8|d.ns.dns.be.        **518400**    IN    AAAA    2001:678:6c:0:0:0:0:1|
|a.nic.brussels.        **172800**    IN    A    194.0.6.1|**d.ns.dns.be.        518400    IN    A    194.0.44.1**|
|a.nic.brussels.        **172800**    IN    AAAA    2001:678:9:0:0:0:0:1|y.ns.dns.be.        **518400**    IN    A    120.29.253.8|
|b.nic.brussels.        **172800**    IN    A    194.0.37.1|y.ns.dns.be.        **518400**    IN    AAAA    2001:dcd:7:0:0:0:0:8|
|**b**.**nic**.brussels.        **172800**    IN    AAAA    **2001:678:64:0:0:0:0:1**|a.nic.brussels.        **518400**    IN    A    194.0.6.1|
|z.nsset.brussels.    **172800**    IN    A    194.0.25.14|a.nic.brussels.        **518400**    IN    AAAA    2001:678:9:0:0:0:0:1|
|**z.nsset.brussels.    172800    IN    AAAA    2001:678:20:0:0:0:0:14**|b.nic.brussels.        **518400**    IN    **AAAA    2001:678:64:0:0:0:0:1**|
||**b.nic.brussels.        518400    IN    **A    194.0.37.1|
||**z**.**nsset**.brussels.    **518400**    IN    AAAA    **2001:678:20:0:0:0:0:14**|
||z.nsset.brussels.    **518400**    IN    A    194.0.25.14|
#
## travelers
|expected|actual|
|--------|---|
|travelers.        86400    IN    DS    **967** **8** **2** **975D9FD3B056E286263F680F31106C7509ED466EAE0AA08B3B045ABAE39945F6**|travelers.        86400    IN    DS    **55405** **7** **1** **4DE444AB5096A42A5536C5E73D92AE0E4A3925FA**|
|**a0.nic.**travelers.    **172800**    IN    **A**    **65.22.200.9**|travelers.        **86400**    IN    **DS**    **55405** **7 2 4597259FC2C930D955185465CB7CCE4F7B4258C0797C9F639AA5153A1F848651**|
|a0.nic.travelers.    **172800**    IN    AAAA    2a01:8840:c2:0:0:0:0:9|a0.nic.travelers.    **518400**    IN    AAAA    2a01:8840:c2:0:0:0:0:9|
|**a2**.nic.travelers.    **172800**    IN    A    65.22.**203**.9|**a0**.nic.travelers.    **518400**    IN    A    65.22.**200**.9|
|a2.nic.travelers.    **172800**    IN    AAAA    2a01:8840:c5:0:0:0:0:9|a2.nic.travelers.    **518400**    IN    AAAA    2a01:8840:c5:0:0:0:0:9|
|b0.nic.travelers.    **172800**    IN    A    65.22.201.9|**a2.nic.travelers.    518400    IN    A    65.22.203.9**|
|b0.nic.travelers.    **172800**    IN    AAAA    2a01:8840:c3:0:0:0:0:9|b0.nic.travelers.    **518400**    IN    A    65.22.201.9|
|c0.nic.travelers.    **172800**    IN    A    65.22.202.9|b0.nic.travelers.    **518400**    IN    AAAA    2a01:8840:c3:0:0:0:0:9|
|c0.nic.travelers.    **172800**    IN    AAAA    2a01:8840:c4:0:0:0:0:9|c0.nic.travelers.    **518400**    IN    A    65.22.202.9|
||c0.nic.travelers.    **518400**    IN    AAAA    2a01:8840:c4:0:0:0:0:9|
#
## zara
|expected|actual|
|--------|---|
|zara.            86400    IN    DS    **40147** **8** **2** **2E4669652E0C3B84007E43707F8354C94AFD6F929A5152524BEDBAA6F009DAFA**|zara.            86400    IN    DS    **26743** **7** **1** **DB311C639714F0505A423A450341117FEC68B4B5**|
|**a0.nic.**zara.        **172800**    IN    **A**    **65.22.232.33**|zara.            **86400**    IN    **DS**    **26743** **7 2 8C5921F2924E3B6EC6504A7FF9448924A877707FDCB283F3D6C2D7B59555BC76**|
|a0.nic.zara.        **172800**    IN    AAAA    2a01:8840:e2:0:0:0:0:33|a0.nic.zara.        **518400**    IN    AAAA    2a01:8840:e2:0:0:0:0:33|
|**a2**.nic.zara.        **172800**    IN    A    65.22.**235**.33|**a0**.nic.zara.        **518400**    IN    A    65.22.**232**.33|
|a2.nic.zara.        **172800**    IN    AAAA    2a01:8840:e5:0:0:0:0:33|a2.nic.zara.        **518400**    IN    AAAA    2a01:8840:e5:0:0:0:0:33|
|**b0**.nic.zara.        **172800**    IN    A    65.22.**233**.33|**a2**.nic.zara.        **518400**    IN    A    65.22.**235**.33|
|b0.nic.zara.        **172800**    IN    AAAA    2a01:8840:e3:0:0:0:0:33|b0.nic.zara.        **518400**    IN    AAAA    2a01:8840:e3:0:0:0:0:33|
|**c0**.nic.zara.        **172800**    IN    A    65.22.**234**.33|**b0**.nic.zara.        **518400**    IN    A    65.22.**233**.33|
|c0.nic.zara.        **172800**    IN    AAAA    2a01:8840:e4:0:0:0:0:33|c0.nic.zara.        **518400**    IN    AAAA    2a01:8840:e4:0:0:0:0:33|
||**c0.nic.zara.        518400    IN    A    65.22.234.33**|
#
## travelchannel
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## kuokgroup
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## sncf
|expected|actual|
|--------|---|
||**sncf.            86400    IN    DS    36355 8 2 F26DBB78243D733E151A2D027CBA30C8A88D60BD0453E684973B4EB34BF01A8D**|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
||g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
#
## citic
|expected|actual|
|--------|---|
|a.zdnscloud.com.    **172800**    IN    A    203.99.24.1|a.zdnscloud.com.    **518400**    IN    A    203.99.24.1|
|b.zdnscloud.com.    **172800**    IN    A    203.99.25.1|b.zdnscloud.com.    **518400**    IN    A    203.99.25.1|
|c.zdnscloud.com.    **172800**    IN    A    203.99.26.1|c.zdnscloud.com.    **518400**    IN    A    203.99.26.1|
|d.zdnscloud.com.    **172800**    IN    A    203.99.27.1|d.zdnscloud.com.    **518400**    IN    A    203.99.27.1|
|f.zdnscloud.com.    **172800**    IN    A    114.67.**16**.**204**|f.zdnscloud.com.    **518400**    IN    A    114.67.**46**.**12**|
|g.zdnscloud.com.    **172800**    IN    A    42.62.2.16|g.zdnscloud.com.    **518400**    IN    A    42.62.2.16|
|i.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:1:0:0:0:0:1|i.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:1:0:0:0:0:1|
|j.zdnscloud.com.    **172800**    IN    AAAA    2401:8d00:2:0:0:0:0:1|j.zdnscloud.com.    **518400**    IN    AAAA    2401:8d00:2:0:0:0:0:1|
#
## hair
|expected|actual|
|--------|---|
|hair.            172800    IN    NS    **a**.**nic**.**hair**.|hair.            172800    IN    NS    **ac1**.**nstld**.**com**.|
|hair.            172800    IN    NS    **b**.**nic**.**hair**.|hair.            172800    IN    NS    **ac2**.**nstld**.**com**.|
|hair.            172800    IN    NS    **c**.**nic**.**hair**.|hair.            172800    IN    NS    **ac3**.**nstld**.**com**.|
|hair.            172800    IN    NS    **d**.**nic**.**hair**.|hair.            172800    IN    NS    **ac4**.**nstld**.**com**.|
|**hair**.**            86400    IN    DS    39236 8 2 D8C88DAA478496C4F99A8CB5CACB0746CDDE2612E9668BEB6F7D683AC220313B**|**ac1**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**176**.**30**|
|**a**.**nic**.**hair.**        **172800**    IN    A    **194**.**169**.**218**.**117**|**ac2**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**174**.**30**|
|**a**.**nic**.**hair**.        **172800**    IN    **AAAA    2001:67c:13cc:0:0:0:1:117**|**ac2**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:121:0:0:0:0:30**|
|**b.nic.hair.        172800    IN    **A    **185**.**24**.**64**.**117**|**ac3**.**nstld**.**com**.        **518400**    IN    A    **192**.**42**.**175**.**30**|
|**b**.**nic**.**hair**.        **172800**    IN    AAAA    **2a04:2b00:13cc:0:0:0:1:117**|**ac3**.**nstld**.**com**.        **518400**    IN    AAAA    **2001:500:122:0:0:0:0:30**|
|**c**.**nic**.**hair**.        **172800**    IN    A    **212**.**18**.**248**.**117**|**ac4**.**nstld**.**com**.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|**c**.**nic**.**hair**.        **172800**    IN    AAAA    **2a04:2b00:13ee:0:0:0:0:117**|**ac4**.**nstld**.**com**.        **518400**    IN    **A**    **192.42.176.30**|
|**d**.**nic**.**hair**.        **172800**    IN    **A**    **212.18.249.117**||
|**d**.**nic**.**hair**.        **172800**    IN    **AAAA**    **2a04:2b00:13ff:0:0:0:0:117**||
#
## security
|expected|actual|
|--------|---|
||**security.        172800    IN    NS    c.nic.security.**|
||**security.        172800    IN    NS    d.nic.security.**|
||**security.        86400    IN    DS    14150 8 1 E14122358E5F8AFC204A70C4D71F312D7C6595BB**|
|a.nic.security.        **172800**    IN    **A**    **194.169.218.68**|a.nic.security.        **518400**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:68**|
|a.nic.security.        **172800**    IN    **AAAA**    **2001:67c:13cc:0:0:0:1:68**|a.nic.security.        **518400**    IN    **A**    **194.169.218.68**|
|b.nic.security.        **172800**    IN    A    185.24.64.68|b.nic.security.        **518400**    IN    A    185.24.64.68|
|b.nic.security.        **172800**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:68|b.nic.security.        **518400**    IN    AAAA    2a04:2b00:13cc:0:0:0:1:68|
|**e**.nic.security.        **172800**    IN    A    **212**.**18**.**248**.**68**|**c**.nic.security.        **518400**    IN    **AAAA    2a02:e180:3:0:0:0:0:9**|
|e.nic.security.        **172800**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:68|**c.nic.security.        518400    IN    **A    **185**.**38**.**99**.**9**|
|**f**.nic.security.        **172800**    IN    A    212.18.**249**.68|**d.nic.security.        518400    IN    A    108.59.161.9**|
|f.nic.security.        **172800**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:68|**d.nic.security.        518400    IN    AAAA    2a02:e180:4:0:0:0:0:9**|
||e.nic.security.        **518400**    IN    AAAA    2a04:2b00:13ee:0:0:0:0:68|
||**e**.nic.security.        **518400**    IN    A    212.18.**248**.68|
||f.nic.security.        **518400**    IN    AAAA    2a04:2b00:13ff:0:0:0:0:68|
||**f.nic.security.        518400    IN    A    212.18.249.68**|
#
## paris
|expected|actual|
|--------|---|
|d.nic.fr.        **172800**    IN    A    194.0.9.1|d.nic.fr.        **518400**    IN    **AAAA    2001:678:c:0:0:0:0:1**|
|d.nic.fr.        **172800**    IN    **AAAA**    **2001:678:c:0:0:0:0:1**|**d.nic.fr.        518400    IN    **A    194.0.9.1|
|f.ext.nic.fr.        **172800**    IN    **A**    **194.146.106.46**|d.nic.fr.        **518400**    IN    **A**    **194.0.9.111**|
|f.ext.nic.fr.        **172800**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|f.ext.nic.fr.        **518400**    IN    **AAAA**    **2001:67c:1010:11:0:0:0:53**|
|g.ext.nic.fr.        **172800**    IN    A    194.0.36.1|f.ext.nic.fr.        **518400**    IN    **A**    **194.146.106.46**|
|g.ext.nic.fr.        **172800**    IN    AAAA    2001:678:4c:0:0:0:0:1|g.ext.nic.fr.        **518400**    IN    A    194.0.36.1|
|h.ext.nic.fr.        **172800**    IN    **A**    **195.253.66.2**|g.ext.nic.fr.        **518400**    IN    AAAA    2001:678:4c:0:0:0:0:1|
|h.ext.nic.fr.        **172800**    IN    **AAAA**    **2a01:5b0:6:0:0:0:0:2**|h.ext.nic.fr.        **518400**    IN    **AAAA**    **2a01:5b0:6:0:0:0:0:2**|
||h.ext.nic.fr.        **518400**    IN    **A**    **195.253.66.2**|
#
## car
|expected|actual|
|--------|---|
|**car.            172800    IN    NS    a.nic.car.**||
|**car.            172800    IN    NS    b.nic.car.**||
|**car.            172800    IN    NS    c.nic.car.**||
|**car.            172800    IN    NS    d.nic.car.**||
|car.            86400    IN    DS    **6293** 5 1 **5F4D85436E50896F89715EE4BB9F18F4B8C876D5**|car.            86400    IN    DS    **22307** 5 1 **A829D7EAE806E497132B46179DCC5B8824010320**|
|car.            86400    IN    DS    **6293** 5 2 **519D12765966B6F6E6BE8236B0A6510B86025FDC7BCBAA1630B8632A9471A4D3**|car.            86400    IN    DS    **22307** 5 2 **EF40B9A2A119F93103931DB003BE4EF9B2C97437DA26F4EA519555499A71B64E**|
||**car.            86400    IN    DS    64561 5 2 D89C304C66E6377AA7825C3A1A348DE1EAE69D6FA75902A6F927F903E2B91E58**|
|**car.            86400    IN    DS    14236 5 2 A35069C1E396B842C2BCBEB250C72E33C41FFDB0B053074D35A47C5B3E99791A**||
|car.            86400    IN    DS    **64561** 5 2 **D89C304C66E6377AA7825C3A1A348DE1EAE69D6FA75902A6F927F903E2B91E58**|car.            86400    IN    DS    **14236** 5 2 **A35069C1E396B842C2BCBEB250C72E33C41FFDB0B053074D35A47C5B3E99791A**|
|**a**.**nic**.**car**.        **172800**    IN    A    **194.169.218.130**|**ns2**.**uniregistry**.**info**.    **518400**    IN    A    64.**96**.**2**.**1**|
|**a.nic.car.        172800    IN    AAAA    2001:67c:13cc:0:0:0:1:130**|**ns4**.uniregistry.info.    **518400**    IN    **AAAA**    **2620:10a:80ab:0:0:0:0:3**|
|**b.nic.car.        172800    IN    A    185.24.**64.**130**|ns4.uniregistry.info.    **518400**    IN    A    185.159.198.3|
|**b**.**nic**.**car.**        **172800    IN    AAAA    2a04:2b00:13cc:0:0:0:1:130**|**ns1**.uniregistry.**net**.    **518400**    IN    AAAA    **2620:57:4000:1:0:0:0:1**|
|**c**.**nic.car.        172800    IN    A    212.18.248.130**|ns1.uniregistry.net.    **518400**    IN    A    64.96.1.1|
|**c.nic.car.        172800    IN    AAAA    2a04:2b00:13ee:0:0:0:0:130**|ns3.uniregistry.net.    **518400**    IN    A    185.159.197.3|
|**d.nic.car.        172800    IN    A    212.18.249.130**|ns3.uniregistry.net.    **518400**    IN    AAAA    2620:10a:80aa:0:0:0:0:3|
|**d.nic.car.        172800    IN    AAAA    2a04:2b00:13ff:0:0:0:0:130**||
|**ns2.**uniregistry.info.    **172800**    IN    **A**    **64.96.2.1**||
|ns4.uniregistry.info.    **172800**    IN    A    185.159.198.3||
|**ns4**.uniregistry.**info**.    **172800**    IN    AAAA    **2620:10a:80ab:0:0:0:0:3**||
|ns1.uniregistry.net.    **172800**    IN    A    64.96.1.1||
|**ns1.uniregistry.net.    172800    IN    AAAA    2620:57:4000:1:0:0:0:1**||
|ns3.uniregistry.net.    **172800**    IN    A    185.159.197.3||
|ns3.uniregistry.net.    **172800**    IN    AAAA    2620:10a:80aa:0:0:0:0:3||
#
## tci
|expected|actual|
|--------|---|
|ns.cocca.fr.        **172800**    IN    A    185.17.236.93|ns.cocca.fr.        **518400**    IN    A    185.17.236.93|
|ns.cocca.fr.        **172800**    IN    AAAA    2a03:dd40:3:0:0:0:0:93|ns.cocca.fr.        **518400**    IN    **A    185.17.236.123**|
|a.ns.nic.tci.        **172800**    IN    **A**    **72.0.49.8**|**ns.cocca.fr.        518400    IN    **AAAA    2a03:dd40:3:0:0:0:0:93|
|a.ns.nic.tci.        **172800**    IN    **AAAA**    **2620:171:a01:ad:0:0:0:8**|a.ns.nic.tci.        **518400**    IN    **AAAA**    **2620:171:a01:ad:0:0:0:8**|
|b.ns.nic.tci.        **172800**    IN    AAAA    2620:171:d01:dc:0:0:0:8|a.ns.nic.tci.        **518400**    IN    **A**    **72.0.49.8**|
|b.ns.nic.tci.        **172800**    IN    A    72.42.113.8|b.ns.nic.tci.        **518400**    IN    AAAA    2620:171:d01:dc:0:0:0:8|
||b.ns.nic.tci.        **518400**    IN    A    72.42.113.8|
#
## hgtv
|expected|actual|
|--------|---|
|ac1.nstld.com.        **172800**    IN    A    192.42.**173**.30|ac1.nstld.com.        **518400**    IN    A    192.42.**176**.30|
|**ac1.nstld.com.        172800    IN    AAAA    2001:500:120:0:0:0:0:30**|ac2.nstld.com.        **518400**    IN    A    192.42.174.30|
|ac2.nstld.com.        **172800**    IN    A    192.42.174.30|ac2.nstld.com.        **518400**    IN    AAAA    2001:500:121:0:0:0:0:30|
|ac2.nstld.com.        **172800**    IN    AAAA    2001:500:121:0:0:0:0:30|ac3.nstld.com.        **518400**    IN    A    192.42.175.30|
|ac3.nstld.com.        **172800**    IN    A    192.42.175.30|ac3.nstld.com.        **518400**    IN    AAAA    2001:500:122:0:0:0:0:30|
|ac3.nstld.com.        **172800**    IN    AAAA    2001:500:122:0:0:0:0:30|ac4.nstld.com.        **518400**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**|
|ac4.nstld.com.        **172800**    IN    **A**    **192.42.176.30**|ac4.nstld.com.        **518400**    IN    **A**    **192.42.176.30**|
|ac4.nstld.com.        **172800**    IN    **AAAA**    **2001:500:123:0:0:0:0:30**||
#
## cbs
|expected|actual|
|--------|---|
|cbs.            86400    IN    DS    **30409** **8** 2 **EA9D4289FAB50BAB2A4F682A1F450A0D5B7802AAC66B478703BE109FBD489959**|cbs.            86400    IN    DS    **7539** **7** **1 B29B8D3B6BDB075F5F37D476C8B2A52E36FC5DE9**|
|a0.nic.cbs.        **172800**    IN    A    65.22.68.9|**cbs.            86400    IN    DS    7539 7 **2 **506142CC0504F515838D01A7AC0F7B3B25C5F301425C6615F87976759D5270F7**|
|a0.nic.cbs.        **172800**    IN    AAAA    2a01:8840:42:0:0:0:0:9|a0.nic.cbs.        **518400**    IN    A    65.22.68.9|
|a2.nic.cbs.        **172800**    IN    **A**    **65.22.71.9**|a0.nic.cbs.        **518400**    IN    AAAA    2a01:8840:42:0:0:0:0:9|
|a2.nic.cbs.        **172800**    IN    **AAAA**    **2a01:8840:45:0:0:0:0:9**|a2.nic.cbs.        **518400**    IN    **AAAA**    **2a01:8840:45:0:0:0:0:9**|
|b0.nic.cbs.        **172800**    IN    **AAAA**    **2a01:8840:43:0:0:0:0:9**|a2.nic.cbs.        **518400**    IN    **A**    **65.22.71.9**|
|b0.nic.cbs.        **172800**    IN    **A**    **65.22.69.9**|b0.nic.cbs.        **518400**    IN    **A**    **65.22.69.9**|
|c0.nic.cbs.        **172800**    IN    A    65.22.70.9|b0.nic.cbs.        **518400**    IN    **AAAA**    **2a01:8840:43:0:0:0:0:9**|
|c0.nic.cbs.        **172800**    IN    AAAA    2a01:8840:44:0:0:0:0:9|c0.nic.cbs.        **518400**    IN    A    65.22.70.9|
||c0.nic.cbs.        **518400**    IN    AAAA    2a01:8840:44:0:0:0:0:9|
#
