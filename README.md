

Copy data from azre SQL to ADLS

{
	"dataRead": 0,
	"dataWritten": 33,
	"filesWritten": 1,
	"sourcePeakConnections": 1,
	"sinkPeakConnections": 1,
	"rowsRead": 0,
	"rowsCopied": 0,
	"copyDuration": 10,
	"throughput": 0,
	"errors": [],
	"effectiveIntegrationRuntime": "AutoResolveIntegrationRuntime (East US)",
	"usedDataIntegrationUnits": 4,
	"billingReference": {
		"activityType": "DataMovement",
		"billableDuration": [
			{
				"meterType": "AzureIR",
				"duration": 0.06666666666666667,
				"unit": "DIUHours"
			}
		],
		"totalBillableDuration": [
			{
				"meterType": "AzureIR",
				"duration": 0.06666666666666667,
				"unit": "DIUHours"
			}
		]
	},
	"usedParallelCopies": 1,
	"executionDetails": [
		{
			"source": {
				"type": "AzureSqlDatabase",
				"region": "West US 2"
			},
			"sink": {
				"type": "AzureBlobFS",
				"region": "East US"
			},
			"status": "Succeeded",
			"start": "6/14/2025, 7:47:13 PM",
			"duration": 10,
			"usedDataIntegrationUnits": 4,
			"usedParallelCopies": 1,
			"profile": {
				"queue": {
					"status": "Completed",
					"duration": 5
				},
				"transfer": {
					"status": "Completed",
					"duration": 3,
					"details": {
						"readingFromSource": {
							"type": "AzureSqlDatabase",
							"workingDuration": 0,
							"timeToFirstByte": 1
						},
						"writingToSink": {
							"type": "AzureBlobFS",
							"workingDuration": 0
						}
					}
				}
			},
			"detailedDurations": {
				"queuingDuration": 5,
				"timeToFirstByte": 1,
				"transferDuration": 2
			}
		}
	],
	"dataConsistencyVerification": {
		"VerificationResult": "NotVerified"
	},
	"durationInQueue": {
		"integrationRuntimeQueue": 0
	}
}
