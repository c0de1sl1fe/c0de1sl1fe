<h2> Hi there 🌱 </h2>
![visitors](https://visitor-badge.laobi.icu/badge?page_id=c0de1sl1fe.c0de1sl1fe)
<img align='right' src="https://giphy.com/embed/vzO0Vc8b2VBLi" width="230">

``` java
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
