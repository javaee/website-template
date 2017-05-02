

# About

{{site.title}} is a simple demo site. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor ut labore et dolore aliqua. Ut enim ad minim veniam, quis exercitation ullamco laboris nisi ut aliquip.


Lorem ipsum dolor sit amet again! Consectetur adipiscing elit, sed do eiusmod tempor ut labore et dolore aliqua. Ut enim ad minim veniam, quis exercitation ullamco laboris nisi.


  
# H1 Java Enterprise GlassFish

Some content

## H2 Java Enterprise GlassFish

Some content

### H3 Java Enterprise GlassFish

Some content

#### H4 Java Enterprise GlassFish

| File  | Description |
| :---: | :--- |
| [javax.mail.jar](https://github.com/javaee/javamail/releases/download/JAVAMAIL-1_5_6/javax.mail.jar)  | The JavaMail reference implementation, including the SMTP, IMAP, and POP3 protocol providers  |
| [README.txt](https://bshannon.github.io/test/docs/README.txt) | Overview of the release |
| [NOTES.txt](https://bshannon.github.io/test/docs/NOTES.txt)	|Additional notes about using JavaMail  |
| [SSLNOTES.txt](https://bshannon.github.io/test/docs/SSLNOTES.txt)	|Notes on using SSL/TLS with JavaMail  |

|jar file|gropuId|artifactId|Description|
| :---: | :---: |  :---: | :--- | 
| javax.mail.jar | com.sun.mail | javax.mail | The JavaMail reference implementation jar file, including the SMTP, IMAP, and POP3 protocol providers |
| javax.mail-api.jar | javax.mail | javax.mail-api | The JavaMail API definitions only, suitable for compiling against |
| mailapi.jar | com.sun.mail | mailapi | The JavaMail reference implementation with no protocol providers; use with one of the following providers |
| smtp.jar | com.sun.mail | smtp | The SMTP protocol provider |

# To Do

* Fix bug
* Improve formatting
* Make the headings bigger
* Push my commits to GitHub
  
# Latest News

## April 1st, 2017 - Java.net migration! ##

All the {{site.title}} assets has been moved from Java.net to a new location.

## April 10th, 2017 - JAX-RS PATCH support (client API) ##

PATCH support has been added to JAX-RS API 2.1 in milestone 6, see [here](https://java.net/projects/jax-rs-spec/lists/users/archive/2017-04/message/40).
Check the [contribute](contribute) page which is a full page.

```java
/**
 * Indicates that the annotated method responds to HTTP PATCH requests.
 *
 * @author Pavel Bucek (pavel.bucek at oracle.com)
 * @see HttpMethod
 * @since 2.1
 */
@Target({ElementType.METHOD})
@Retention(RetentionPolicy.RUNTIME)
@HttpMethod(HttpMethod.GET)
@Documented
public @interface PATCH {
}
```


