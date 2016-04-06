	   
###2.2 WKWebView     
在iOS 8及其以后的版本，建议使用WKWebView代替UIWebView，这样性能更高，加载速度提升了，内存反而降低了。所以苹果建议开发者使用WKWebView代替UIWebView。    
            
####2.2.1 WKWebView加载网页 
      
	WKWebView *webView = [[WKWebView alloc]initWithFrame:self.view.bounds];
	[webView loadRequest:[NSURLRequest requestWithURL:[NSURL URLWithString:@"https://m.baidu.com/"]]];
	[self.view addSubview:webView];     

####2.2.2 WKNavigationDelegate协议     

####2.2.3 WKUIDelegate

####2.2.4 WKScriptMessageHandler

####2.2.5 WKWebView加载JS