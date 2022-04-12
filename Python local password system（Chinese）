while True:
    NoneLogin = input("输入Login登录！或输入Register注册、Forget Plassword找回密码")
    if NoneLogin =="Register":
            print("一个机子只能注册一个，否则出错！可以修改密码或名称")
            with open("Administor/Name.TBNTinertSafetxt","a+") as Fire223:
                Name = input("输入名称")
                Fire223.write(Name)
            with open("Administor/Plassword.TBNTinertSafetxt","a+") as Fire222:
                Plassword = input("输入密码")
                Fire222.write(Plassword)
            break
    if "Login" in NoneLogin:
        with open("Administor/Name.TBNTinertSafetxt","r") as ReadName:
            LName = input("输入账户名称")
            if (ReadName.read()) == LName:
                print("这个账户可用，请输入密码")
            else:
                print("你的账户不在机器库中或不存在此账号")
        with open("Administor/Plassword.TBNTinertSafetxt","r") as ReadPlassword:
            LP = input("输入密码")
            if (ReadPlassword.read()) == LP:
                break
            else:
                print("你的账户或密码错误")
