valentine_2020.html 사용시 재생 주소<br>https://github아이디.github.io/Repository이름/valentine_2020.html<br>대체 파일 사용시 재생 주소<br>https://github아이디.github.io/Repository이름/campaigns/valentine_present/show_flash_present_chocolate/2020/아이돌숫자.html

이 주소 아이디랑 repository이름에 맞게 바꿔서 누르면 재생됨<br>↑저기서 <>Code 위에 보면 아이디/repository순서로 나와있음

------------------------------------------

valentine_2020.html에서 수정할 부분

70줄, 71줄에서

            "replace_target_480x502_character": "campaign/valentine/2018/idol/89.png",
            
            "replace_target_240x310_bg": "campaign/valentine/2018/bg/9.jpg"
            
bg 뒤의 숫자9가 배경이니 1~14 중 자기 아이돌 배경이랑 맞는 숫자로 고쳐주면 됨<br>이건 파일은 내가 다 넣어뒀으니 아마 대부분은 숫자만 바꿔주면 될 것

idol 뒤의 숫자 89는 아이돌 번호인데 이건 너무 많아서 내가 안넣어뒀음<br>직접 자기 아이돌 이미지 찾아서 경로에 업로드한 다음 그 파일명으로 바꿔주셈

------------------------------------------

텍스트같은 경우 76줄부터

            "place_name": "OO(장소)",
            "txt1": "대사1(출력X)",
            "txt1_1": "대사1_1줄",
            "txt1_2": "대사1_2줄",
            "txt1_3": "대사1_3줄",
            "txt1_4": "대사1_4줄",
            "txt2": "OO로부터 발렌타인 선물을 받았다(출력X)",
            "txt2_1": "OOからﾊﾞﾚﾝﾀｲﾝのﾌﾟﾚｾﾞﾝﾄを",
            "txt2_2": "もらった｡",
            "txt3": "대사2(출력X)",
            "txt3_1": "대사2_1줄",
            "txt3_2": "대사2_2줄",
            "txt3_3": "대사2_3줄",
            "txt3_4": "대사2_4줄",
            "txt4": "OO과의 사이에 또 1가지 추억이 늘었다(출력X)",
            "txt4_1": "OOとの間にまた1つ思い出",
            "txt4_2": "が増えた｡"

이 부분을 바꿔주면 되는데 txt1 txt2 txt3 txt4는 그 밑의 대사들이 합쳐져서 어떻게 보이는가고 실제로 출력은 안됨<br>txt1_1, txt1_2 등이 모여서 실제로 출력되는 대사가 나오니까 그걸 맞춰서 자기 아이돌 대사 넣어주면 됨
