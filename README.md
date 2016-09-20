
用于隐藏控件的高度或宽度，且不占位，自动布局的情况下，可视控件自动填充。（源自于作者dreyhomedev，但原程序有BUG，此程序是在原程序基础上进行的修改，在此感谢原作者）


案例
import "UIView+DHNHideByConstraints.h"

- (void)hideViews {

[self.myViewToHide1 hideVertical:YES];
[self.myViewToHide2 hideHorizontal:YES];

}

- (void)showViews {

[self.myViewToHide1 hideVertical:NO];
[self.myViewToHide2 hideHorizontal:NO];

}
