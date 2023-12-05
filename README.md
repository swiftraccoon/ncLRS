# ncLRS
https://lrs.sog.unc.edu/
The Legislative Reporting Service website provides immediate access to the daily business of the North Carolina General Assembly. This robust online tool replaces the School’s traditional Daily Bulletin.

https://www.ncleg.gov/Search/BillText?sBillType=0&sBillChamber=0&sSession=2023&sSortBy=0&sSearchText=dog
https://www.ncleg.gov/Search/BillText
{
	"Request Cookies": {
		"DefaultSearchOption": "bill"
	}
}
sBillType=0&sBillChamber=0&sSession=2023&sSortBy=0&sSearchText=cannabis
{
	"POST": {
		"scheme": "https",
		"host": "www.ncleg.gov",
		"filename": "/Search/BillText",
		"remote": {
			"Address": "12.202.62.23:443"
		}
	}
}

HTTP/1.1 200 OK
Cache-Control: private
Content-Type: text/html; charset=utf-8
Server: Microsoft-IIS/10.0
X-AspNetMvc-Version: 5.2
X-AspNet-Version: 4.0.30319
Content-Security-Policy: frame-ancestors 'self' https://sites.ncleg.gov
Strict-Transport-Security: max-age=31536000; includeSubdomains; preload
Access-Control-Allow-Origin: https://www.ncleg.gov
Date: Mon, 04 Dec 2023 07:46:48 GMT
Content-Length: 42665

POST /Search/BillText HTTP/1.1
Host: www.ncleg.gov
User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/119.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate, br
Content-Type: application/x-www-form-urlencoded
Content-Length: 71
Origin: https://www.ncleg.gov
Connection: keep-alive
Referer: https://www.ncleg.gov/Search/BillText
Cookie: DefaultSearchOption=bill
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: same-origin
Sec-Fetch-User: ?1
DNT: 1
Sec-GPC: 1