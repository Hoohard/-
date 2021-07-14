#include "stdafx.h"

int main(int argc, char* argv[])
{
	int val;
	printf("请输入您要进入的楼层：\n");
	scanf("%d", &val);

	while (val!=9999){
	switch (val){
	case 1:
		printf("1层开！");
		break;
	case 2:
		printf("2层开！");
		break;
	case 3:
		printf("3层开！");
		break;
	default:
		printf("这一层没有建到！");
		break;
	}
	scanf("%d", &val);
	}
	return 0;
}
