# E_03 회고록  

----  

여러 사진을 사용해보고 sticker에서 배경으로 사용되는 색상도 조절해봄.  
머리까지 전부 나와야 얼굴로 인식해주는 듯 했다. 몇 몇 사진의 머리 일부가  
사진에 나오지 않았더니 얼굴로 인식하지 못했다.  
cv2.warpAffine()를 이용해 sticker의 각도를 변경하여 사진에 넣었으나,  
area설정을 제대로 하지 못해 sticker의 일부가 잘려나갔다.  
area설정을 손보면서 아직 데이터의 배열에 대한 개념이 부족하다고 느꼈다.  
추가로 배열에 대한 공부를 더 해야하고, 다시 도전해볼 계획.  
검색을 해보니 detector_hog()말고도 다른 방식으로 얼굴을 찾는 기능들이 있었는데,  
몇 가지 더 사용해보는 것도 좋을 듯.  
LMS와 검색을 통해 cv2.addWeighted()를 사용하여 이미지의 투명도(상대적)를  
변경할 수 있다고 하는데, 이미지 두개를 비율로 겹쳐주는 것 같아 기존의 코드에서 사용하려면  
많이 수정해서 사용해야할 듯.  
이상 마무리.