# Hi there 🌱
![visitors](https://visitor-badge.laobi.icu/badge?page_id=zhenye-na.zhenye-na)

``` java
public class Main {
    public static void main(String[] args) {
        Myself me = Myself.getMyself();
        me.introduce();
    }
}


class Myself implements Python, Java {
    private Map<String, String> info;
    public static Myself getMyself() {
        return new Myself();
    }
    private Myself() {
        info = new LinkedHashMap<>();
        info.put("name", "Yuri");
        info.put("lang", "Eng, Ru");
        info.put("level", "trainee");
    }
    public void introduce() {
        System.out.println(info);
        getPythonStack();
        getJavaStack();
    }
    @Override
    public void getPythonStack() {
        System.out.println( "Python core" +
                            "Matplotlib" +
                            "NumPy" +
                            "PyQt");
    }
    @Override
    public void getJavaStack() {
        System.out.println("JavaSE");
    }
}
interface Python {
    public void getPythonStack();
}
interface Java {
    public void getJavaStack();
}

```
