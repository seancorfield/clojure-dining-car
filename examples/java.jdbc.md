# Using SQLite

In your project.clj, :dependencies:

```clojure
[org.clojure/java.jdbc "0.2.3"]
[org.xerial/sqlite-jdbc "3.7.2"]
```

(or whatever the current versions are).

At the top of your source code:

```clojure
(ns foo-bar.core
  (:require [clojure.java.jdbc :as jdbc]))
```

then in your code, have a db-spec like:

```clojure
(def db-spec {:classname "org.sqlite.JDBC"
              :subprotocol "sqlite"
              :subname "my-db-file.db"})
```
