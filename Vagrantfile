Vagrant.configure("2") do |config|
  config.vm.box = "aws-dummy"

  config.vm.provider :aws do |aws, override|
    aws.access_key_id = "AKIA3SO7AUGDFTDY3W34"
    aws.secret_access_key = "gV3JpwcRs2Qv22/7YR7I/n0MQmnh0dYGAH4Fna2w"
    aws.keypair_name = "mac-office"

    aws.ami = "ami-0b69ea66ff7391e80"

    override.ssh.username = "ec2-user"
    override.ssh.private_key_path = "/home/ninja/pc/id_rsa"
  end
end
