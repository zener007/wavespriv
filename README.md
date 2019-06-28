# wavespriv
Waves Private Node

Run: "docker-compose up"


API: http://yourip:6816 PASSWORD: WavesRocks!
EXPLORER: http://yourip:8080
DATA SERVICES: http://yourip:3000

Note: This is a work in progress - some things might not work, like the matcher. I still need to figure out how to start it on Waves v1.0.0.

===============================================================

import pywaves as pw

pw.setNode(node = 'https://yourip:6816', chain = 'devnet', chain_id = 'D')

myAddress0 = pw.Address(seed='r6GrZLkXe3ze2DZoFE8sxXhdlnjXnWf9p1ku36QVruRAxjH1VWcAf5ey5G44ytYlYbQyWzr068xYoNAwSIjFVYPoqEJmTdwlGNhQ')

myAddress1 = pw.Address(seed='g9ic38YfYi9uMjVb5eeIdaJ9tS0U9m8GYxvohUFVi8ANEWZ9cEyOj36ZLeInLfD65kDub5tDOqspb7mz8TzlKd2UPnsfpWFBkcr1')

myAddress2 = pw.Address(seed='CFcgpu9qAYgU0UMCbGrDY0sZ5xTetogoXsj0URydia1ikJRRw1RDXji24x6Pl5lh3aZPw7whVhfg5sjzYKo0amhRrH9UwM7lG7gN')

myAddress3 = pw.Address(seed='rYS9eQth0R2NLU6SECrU1bHCCAfGh95uhc6EPRKUoYtP7S8ZrrEwgkFKXpj7LocxlOJBKqkFjNy8w26zj6Kh4zamiPuslnDjsGnd')

===============================================================

Enjoy: 3P3xu31BxFVmvQC17CzeSoTr8w7quFMZWwt  (Waves Mainnet)

Based off: https://github.com/wavesplatform/dev-toolkit
