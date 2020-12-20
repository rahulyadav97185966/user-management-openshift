# user-management-openshift

      oc get clusterrolebinding | grep -i self  :- it shows you the policies
      oc adm policy remove-cluster-role-from-group self-provisioner system:authenticated system:authenticated:oauth
      htpasswd -b /etc/origin/master/htpasswd harry cetterede  :- adds the user and cetterede is password
      htpasswd -b /etc/origin/master/htpasswd sagar cetterede
      cat /etc/origin/master/htpasswd  :- you can check whether the user is added or not.
