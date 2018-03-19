# FootPrints

//占位符(切入3号位):text控件名.placeholder = ""(不聚焦)
testField.placeholder = "please enter the user name"

//弹出提示框(切入2号位)
@IBAction func register(_ sender: AnyObject) {                           //关联有效控件
    if(username.text = "") {
        let alertController = UIAlertController(title: "系统提示", message: "请输入用户名", preferredStyle:
            UIAlertController.alert)
        let cancelAction = UIAlertAction(title: "取消", style: UIAlertActionStyle.cancel, handler: nil)
        let okAction = UIAlerAction(title: "确定",style: UIAlertActionStyle.default, handler: nil)
        alertController.addAction(cancelAction)
        alertController.addAction(okAction)
        self.present(alertController, animated: true, completion: nil)
              
    }
}

//限制文本框字数
  //切入class
  UITextFieldDelegate
  //切入3号位
  text.delegate = self
  //切入4号位
  @objc func handleTap(sender: UITapGestureRecognizer) {
      if




