# Basic Activity Example

�⺻���� ��Ƽ��Ƽ ����, ����, �帧 �� �ǽ��� ���� �����ϱ�

# �ֿ� �н� ����

1. startActivity(Intent( .... ))
    - ��Ƽ��Ƽ ���� �����ϱ�.
    - ���� ��Ƽ��Ƽ�� onPause() ȣ�� ��, Back Stack�� ������. 

2. startActivityForResult(...)
    - �ش� �Լ��� �߻� �� activity�� Finish�� �� onActivityResult(...) �� �߻���Ŵ.
    - requestCode, resultCode�� ��Ƽ��Ƽ�� ȣ�� ����, ����� ���� ������ ���� ����.

3. finish()
    - ��Ƽ��Ƽ ���� �� ���� �ֻ��� ��Ƽ��Ƽ onResume() ����.

4. intent�� putExtra(...)�� ���� �����͸� ��Ƽ��Ƽ �� ���� ����.
    - ���� �������� ���� overwrite�� �Լ����� �����Ѵ�.


# Preview

![](https://github.com/danggai/Kotlin-Android-Examples/blob/master/BasicActivityExample/preview.gif?raw=true)
