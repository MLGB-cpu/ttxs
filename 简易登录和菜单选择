package main

import "fmt"

func main() {
	var name string = "666"
	var pawd string = "123"
	var yourname string
	var yourpawd string
	var pleasewait = false
	var xuanze int
	for i := 0; i < 3; i++ {
		fmt.Print("账号: ")
		fmt.Scanln(&yourname)
		fmt.Print("密码: ")
		fmt.Scanln(&yourpawd)
		if yourname == name && yourpawd == pawd {
			fmt.Println("登录成功")
			pleasewait = true
			break
		} else if yourname != name {
			fmt.Println("账户有误")
		} else {
			fmt.Println("密码错误")
		}

	}
	if pleasewait {
		fmt.Println("欢迎来到老司机汽配城")
		fmt.Println("请选择服务\n1:汽车维修\n2:维护保养\n3:改装配件\n4:返回")
		for {
			fmt.Print("请选择一项服务: ")
			fmt.Scanln(&xuanze)
			if xuanze == 1 {
				fmt.Println("请选择维修种类")
			} else if xuanze == 2 {
				fmt.Println("请选择保养类型")
			} else if xuanze == 3 {
				fmt.Println("请选择配件")
			} else {
				fmt.Println("欢迎下次光临")
				break
			}
		}

	}else{
		fmt.Println("密码输入错误三次请稍后再试")
	}
	
	
}
