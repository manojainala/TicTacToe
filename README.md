# TicTacToe
A python implementation of 5x5 Tic-Tac-Toe, with an AI Opponent that
utilizes either the Minimax or the Monte-Carlo Tree Search algorithms.

For UAF CS605 Artificial Intelligence, Spring 2021

Currently rated by pylint at an X/10, because it's impossible for me to not
optimize a score.

```
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
  name: nginx-ingress
  annotations:
    nginx.ingress.kubernetes.io/use-regex: "true"
spec:
  ingressClassName: nginx
  tls:
  - hosts:
    - alan-for-tf.techolution.com
    secretName: alan-for-tf.techolution.com
  rules:
  - host: "alan-for-tf.techolution.com"
    http:
      paths:
          - path: /
            pathType: ImplementationSpecific
            backend:
              service:
                name: hvpd-frontend
                port: 
                  number: 4200
```
