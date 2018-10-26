repo for my own temporary chart packages while its waiting for PR approval from main repos.


       cd <my chrat location>

  546  helm package .
  547  mv sonatype-nexus-1.14.0.tgz  ~/Documents/work/solutions/git/externel.git/chart-repo/
  548  cd ~/Documents/work/solutions/git/externel.git/chart-repo

  551  helm repo index . --url  https://guptaarvindk.github.io/chart-repo/

  552  git status
  553  git add index.yaml sonatype-nexus-1.14.0.tgz
  554  git commit -av
