<hr>
  <h3>Android 部分</h3>
<hr>

<h3>1.繼承  webview and override OnReceiveError method </h3>

![alt tag](https://github.com/eggeggss/HybridWebViewRender/blob/master/Android.jpg)

<h3>2.Custom Render for WebView</h3>

![alt tag](https://github.com/eggeggss/HybridWebViewRender/blob/master/AndroidWebview.png)



<hr> <h3> iOS 部分 </h3> <hr>


<h3>1.繼承  WKWebview and override decidePolicyForNavigationResponse method </h3>

![alt tag](https://github.com/eggeggss/HybridWebViewRender/blob/master/iOS.jpg)


<h3>2.Custom Render for WebView</h3>


![alt tag](https://github.com/eggeggss/HybridWebViewRender/blob/master/iOSWKWebview.png)


收到ErrorCode再發EventAggregator 或 MessagingCenter 到外面轉到自定義Error Page

參考來源 : https://docs.microsoft.com/zh-tw/xamarin/xamarin-forms/app-fundamentals/custom-renderer/hybridwebview
