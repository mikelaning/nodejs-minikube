use admin
db.auth("admin", "admin-password")
db.createUser({"user":"datadog", "pwd": "Datadog", "roles" : [ {role: 'read', db: 'admin' }, {role: 'clusterMonitor', db: 'admin'}, {role: 'read', db: 'local' }]})