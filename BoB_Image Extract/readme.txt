�� ���α׷��� ������� �̹��� ����(ewf, dd)�� �Է��Ͽ� ���ϴ� �ɼǿ� ���߾� ������ �����ϴ� ���α׷��Դϴ�.

����� ���� ȯ���� ������ �����ϴ�.

- Windows7 64bit �̻�
- Python 2.7.X�� ȯ�� ��ġ
- Pytsk3 �� Pyewf ����� ��ġ�Ǿ� �־�� ��

Pytsk3 : https://github.com/log2timeline/l2tbinaries/blob/master/win32/pytsk3-20160721.1.win32-py2.7.msi
Pyewf : https://github.com/log2timeline/l2tbinaries/blob/master/win32/pyewf-20140608.1.win32-py2.7.msi

����� ���ؼ��� ���� ȭ�鿡�� �м��ϰ��� �ϴ� �̹��� ������ ��γ� ���� ���� �Է��Ͽ��ָ� �˴ϴ�. (screenshot ������ �����ϼŵ� �����ϴ�)
(cmd�� ���ؼ� ���� ������ ������ �̵��Ͻ� �� �ڵ带 �����Ű�� ���� �����ϴ�)

�ɼ��� ���� ���ϴ� ���ϸ� ���� �� �� �ֽ��ϴ�. �ɼ� ������ Python 2.7�� ������ ������

file_size, file_extension, modified_time, created_time, accessed_time, edited_time, file_path�� �̿��Ͽ� ����ڰ� ���ϴ� ��� ������ �� �ֽ��ϴ�.

���� ���� ���ο� ���� �ɼ� ������ �����ϸ� �ǹ̴� ������ �����ϴ�.


(file_size >= 10000 and file_extension == ".pdf") and (not bool(re.search("windows", file_path)) or bool(re.search("2011", str(modified_time))))


������ ũ�Ⱑ 10,000 �̻��̸� Ȯ���ڸ� ".PDF"�� ������ ���� �߿� ���� ��ο� "windows"��� ������ ���ų� Modified Time�� 2011����� ��츸 ���͸��϶�.

���� ��� ���� �̹��� ���Ͽ��� �� ���ǿ� �´� ���ϸ� �����Ͽ� �����Ͽ�  extract_files��� ���� �ȿ� 3���� PDF ������ ����Ǿ����� �� �� �ֽ��ϴ�.
���� report.csv ���Ͽ��� ������ ���Ͽ� ���� 7���� ���� (MACE Time, Ȯ����, ���� ũ��, ��ü ���)�� ������־����� �� �� �ֽ��ϴ�.

