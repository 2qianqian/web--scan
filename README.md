#### 初始化
let qr = new webQr() // 初始实例
var begin = function() { // 开始扫描
  qr.init(document.getElementById('box'))
}
var photograph = function() { // 获取当前的文件的信息
  if (qr.qUM){
    console.log(b.getFile()) // base64
    console.log(b.getFile()) // Blob
    console.log(b.getFile()) // file
  }
}
var stops = function() { // 停止拍照
  if (qr.gUM) {
    qr.stop()
  }
}
