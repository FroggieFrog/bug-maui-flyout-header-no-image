# Solution for issue (https://github.com/dotnet/maui/issues/13242#issue-1579365284)

I just found out that you have to reference the image as `.png` instead of `.svg`.
This is mentioned in docs: https://learn.microsoft.com/en-us/dotnet/maui/user-interface/images/images

So with `.png` it is also working on WinUI. But the image is kind of blurry.
Not sure if this is still a bug or can be closed. Maybe an analyzer or so could check for this type of (user/developer) error.

