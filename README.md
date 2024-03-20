<h2> Hi there 🌱 </h2>
<p>Student of <a href="https://ssau.ru/">Samara University</a>
</br>Now studing Java lang
</p>



![visitors](https://visitor-badge.laobi.icu/badge?page_id=c0de1sl1fe.c0de1sl1fe)
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
```
