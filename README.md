# aosp
import android.os.SystemProperties;

public class Example {
    public static void printProp() {
        String value = SystemProperties.get("persist.custom.hello", "default_value");
        Log.d("CustomProp", "Value: " + value);
    }
}
