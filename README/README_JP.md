# Gotanda is OSINT Web Extension

この拡張はFirefox向けに作成したOSINT拡張です。

Webページ中に表示されているURLなどの情報を各種検索エンジンに投げてくれます。

JavaScriptの練習を兼ねて作りました。拙い処理等もあるかと思います。

## 使い方
Webページ中のURL,Domain等をハイライトして右クリックするとコンテキストメニューにGotandaが表示されます。Linkについてはマウスオーバーして右クリックするとコンテキストメニューに表示されます。

調査したい項目を選んで任意の検索エンジンを使用してください。

## 検索エンジン

|Name|URL|Category|
|:---|:--|:-------|
|Domain Tools|https://whois.domaintools.com/|Whois Lookup|
|ThreatCrowd|https://www.threatcrowd.org/|Domain, IP|
|AbuseIPDB|https://www.abuseipdb.com/|IP|
|HackerTarget|https://hackertarget.com/|IP|
|Censys|https://censys.io/|IP, Domain|
|Shodan|https://shodan.io/|IP, Domain|
|FOFA|https://fofa.so/|IP, Domain|
|VirusTotal|https://virustotal.com/|IP, Domain, URL,Hash|
|Tor Relay Search|https://metrics.torproject.org/|IP,Domain|
|Domain Watch|https://domainwat.ch/|Domain, Email|
|DNSlytics|https://dnslytics.com/|IPv4,IPv6,ASN|
|URLscan|https://urlscan.io/|URL|
|Ultratools|https://www.ultratools.com/|IPv6|
|Wayback Machine|https://web.archive.org|URL|
|aguse|https://www.aguse.jp/|URL|
|check-host|https://check-host.net/|URL|
|FortiGuard|https://fortiguard.com/|CVE|
|Sploitus|https://sploitus.com/|CVE|
|Vulmon|https://vulmon.com/|CVE|
|CXSecurity|https://cxsecurity.com/|CVE|
|Vulncode-DB|https://www.vulncode-db.com/|CVE|
|Malshare|https://malshare.com/|MD5 Hash|
|ThreatCrowd|https://www.threatcrowd.org/|IP,Domain|
|Twitter|https://twitter.com/|SNS|
|Qiita|https://qiita.com|SNS|
|GitHub|https://github.com|SNS|
|Facebook|https://www.facebook.com/|SNS|
|Instagram|https://www.instagram.com/|SNS|
|LinkedIn|https://linkedin.com/|SNS|
|Pinterest|https://www.pinterest.jp|SNS|

SNSに関してはアカウント検索のみです。TL検索やワード検索は実装していません。

## その他

日本語環境向けに作成しています。



