# Standalone Profiles

{% hint style="warning" %}
You **cannot** add a new _VM_ without any _standalone profile_, please create a new one first.
{% endhint %}



See all profiles created for your organization. Each profile is described by its _ID_, _Name_, _Public Key_, _Security Group_ (redirects to another page) and to which _VM_ _the profile is associated_.

![Fig. 1: Standalone Profiles](<../.gitbook/assets/overview (6).png>)



#### Actions

​![](https://files.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJQrhtis3vRAM281R7J%2F-McT0x4NgKkVh0AjATAz%2F-McTcbB-au4V6R\_9I-LI%2Flock.png?alt=media\&token=26c90504-4c1f-4a29-a745-0df86f27f5bc)/​![](https://files.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJQrhtis3vRAM281R7J%2F-McT0x4NgKkVh0AjATAz%2F-McTchESBHx\_eCS1Ew3a%2Funlock.png?alt=media\&token=c4ce659f-7351-4dae-a234-65517335f272)Un/lock profile - if you lock your profile, you can't use it for VM, edit or delete it

​![](https://files.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJQrhtis3vRAM281R7J%2F-Mk6UkgYDAHsPXTIGcfJ%2F-Mk6hrUl1O\_c\_YKd85jN%2Fedit.png?alt=media\&token=392bf2c6-8732-4568-af4d-dd75c3aa0053)Update profile - update policy profile

​​![](https://files.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MJQrhtis3vRAM281R7J%2F-Mk6UkgYDAHsPXTIGcfJ%2F-Mk6hyRbUTQuKygF4kbB%2Fdelete.png?alt=media\&token=048d1ff6-58c8-40c2-adee-b4723a073ce7)Delete - delete non-used and unlocked profiles



### Add Standalone Profile

Create a new profile to access your virtual machine.

![Fig. 2: Add Standalone Profile](../.gitbook/assets/add-profile.png)

_Name_ - choose name for your profile

_Public Key_ - insert your SSH public key to access the VM

_Security Groups_ - optional, protocols **ICMP**, **TCP** and **UDP** are supported

{% hint style="danger" %}
Once the _profile_ is created _SSH key_ **cannot** be edited.
{% endhint %}
