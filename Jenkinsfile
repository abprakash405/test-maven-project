@Library('test-pipeline-library') _
//import com.example.*
import groovy.yaml.YamlSlurper
import org.yaml.snakeyaml.Yaml

//new pipeline(this, "config.yml").execute()
sharedPipeline {
	reponame = "maven-war"
	DeploymentName = "asn-war-example-1.0.0-SNAPSHOT"
	def yaml = readYaml file: "config.yml"
	
}
